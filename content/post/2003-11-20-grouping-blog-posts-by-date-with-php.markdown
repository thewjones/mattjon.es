---
type: post
comments: true
date: 2003-11-20T10:51:00Z

tags:
- Uncategorized
title: Grouping Blog Posts by Date with PHP

wordpress_id: 629
---

If you've noticed this site temporarily (for want of a better phrase) _crapping out_ just recently, it's because the [MySQL](http://www.mysql.com) queries I've been using to retrieve the posts from the database have been pretty badly thought out. Thus, the MySQL server has been getting clogged up with slow queries, rendering the site inaccessible for short periods throughout the day.



	

The most straightforward way of formatting a weblog with [PHP](http://www.php.net) and MySQL is to return each entry with a title, body text and the date it was posted underneath. However, I decided to group my posts together by day with a date header at the top of each day's posts. I came up with a solution that involved querying the database for distinct dates and then doing a sub-query for entries posted on those dates. Simply put, I was using MySQL queries for something that a simple bit of PHP could have handled much more efficiently. 



	

As I've learnt, it's best to keep the number of MySQL queries to a minimum, especially if the database is stored on a shared server where resources are limited. So, the new streamlined PHP I'm using looks something like this.  




    
    
    ".date("d/m/Y", $time)."</h2>n";
      }
      // Set the date of this post for comparison in the next loop
      $previous = date("d/m/Y", $time);
      // Print the blog post
      print "<h3>$title</h3>n";
      print "<p>$body</p>n";
    }
    ?>
    
