Responsive HTML Table
================

### Fit HTML table's in Responsive websites with CSS
![Minion](http://raymonschouwenaar.github.io/responsive-table/dist/images/34f71fa4.responsive-table.jpg)

These days where building all website's responsive. We make everything flexible to fit in screen's of smaller devices with CSS3 Media Queries.

I think none of us build his website's with HTML table's (only beginners who learn HTML). I think every frontend developer hate's table's.

But there is one reason to use HTML table's. Only to display a lot of data, that's where the are ment for! But if you use them in Responsive websites the are a problem. Your website will broke in pieces because the HTML table will not fit in the viewport. But there is a simple solution to make your table fit in the viewport and make the table better view-able. With only 3 lines of CSS.

**The CSS you need is:**
<pre lang="css" toggle="no">
.table {
        width: 100%;
         -webkit-overflow-scrolling: touch;
        overflow-x: auto;
        display: block;
    }
</pre>           
With this simple line's of code, all your HTML table's look good on Responsive websites and will never break your layout in to pieces on mobile devices.

Check [the example](http://raymonschouwenaar.github.io/responsive-table/dist/) and resize your browser or check this page on your smartphone! And watch the table below. You can find the [Github repository here](https://github.com/raymonschouwenaar/responsive-table). Check the folder "dist" for the live version. If you use yeoman? Than you can clone the project and use everything in the repo.

