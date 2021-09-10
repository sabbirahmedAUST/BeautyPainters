# BeautyPainters
BeautyPainters is website where you can find various makeup iteams.Go, visit & Buy.

### What does this do?
This is a [ASP.net][asp] and Sql server based platform.Main goal is to provide a user,admin experince to run a online based shopping platform.Here Makeup based iteams are sold.Boh user,Admin & their corresponding parts are being handled here.

### Project Features:
	 * User & Admin Login
  
	 * Admin Panel: its allows to add Admin, Update,Insert & Delete Product
	   Show user Database,List of Purchased Products ,customers and their details.
     
	 * Products are shown accoring to their Offers.The product with best offer is displayed in home.
  
	 * User Panel : User can logout and login later but their CART will not be changed.When user press PLACE ORDER, only when order is placed.
     
	 * User can Login/Website can get addition info from Facebook/ twitter/Gmail.User can also commment/Share the product through FB as well.
     
	 * CART part is done user friendly. User can customize their cart product add/ delete product as they want. Place order, Give locations, See previous orders as well.
 
### Some ScreenShots of Website
<p align="center">
	
<img src="image/s1.png" width="500"/> 
	</p>
<!-- AUTO-GENERATED-CONTENT:START (TOC:collapse=true&collapseText="Click to expand") -->
<details>
	<p align="center">
<img src="image/s3.png" width="500"/>
 <br />
<img src="image/s4.png" width="500"/>
 <br />
<img src="image/s5.png" width="500"/>
 <br />
<img src="image/s2.png" width="500"/>
</details>
<!-- AUTO-GENERATED-CONTENT:END -->	
</p>

### Future Wroks

    * Add more dynamic fealtures & make it more responsive as possible.
    * Use Sceams to be more dynamic.
    * Add mobile verification of customers.
    * Online Payement.
---
### Setup to run the project
<!-- AUTO-GENERATED-CONTENT:START (TOC:collapse=true&collapseText="Click to expand") -->
<details>
	
It is encouraged to use latest version of Visual Studio & use SQL Server Management Studio 12

1.  Clone or download this repo.
2.  Now Open Visual Studio. File -> Open -> Project Solution
<p align="center">
   <img src="image/1.png" width="800"/>
   </p>
3. Select Solution file  .Open
<p align="center">
    <img src="image/2.png" width="800"/>
       </p>
4. Now open SSMS ( SQL SERVER MANAGEMENT STUDIO) . Connect to your Database engine. Add the SQL **Shopping.mdf & Shopping.ldf** given in SQL folder. 
   Copy Data base Server name 
   <p align="center">
   <img src="image/4.png" width="800"/>
      </p>
5. Now open Server Explorer .Under Data connection  X  means not connected. So delete it.  
   <p align="center">
   <img src="image/6.png" width="800"/>
      </p>
6. Now click the Set new connection icon. Give server name  & database name 
    <p align="center">
    <img src="image/7.png" width="800"/>
       </p>
7. Connection is green now. Means its connected successfully.  
     <p align="center">
     <img src="image/8.png" width="800"/>
        </p>
8.  Now go to **Project->Settings->BeautyPainter Settings** :  Type Choose :Connection String. Now using the button give  
    Server name  & database again. Click ok.  A Connection string is provided there.     
    <p align="center">
    <img src="image/5.png" width="800"/>
       </p>
 9.  Final Step. Now Go to **Solution Explorer-> Web Config.** Chanage accordingly to your server name in the following line .
    <p align="center">
   <img src="image/9.png" width="800"/>
       </p>
 10. You are Good to go. Run the project in yur default browser.
 
</details>
<!-- AUTO-GENERATED-CONTENT:END -->

---
### Software & Tools Used To Make Beauty Painters
[<img align="left" alt="HTML5" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png" />][html]
[<img align="left" alt="CSS3" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png" />][css]
[<img align="left" alt="HTML5" width="26px" src="image/database.png" />][database]
[<img align="left" alt="HTML5" width="26px" src="image/aspi.png" />][aspi]

[aspi]: https://github.com/sabbirahmedAUST/BeautyPainters/tree/master/image/aspi.png
 [database]: https://github.com/sabbirahmedAUST/BeautyPainters/tree/master/image/database.png
[asp]: https://dotnet.microsoft.com/apps/aspnet 
[html]: https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png
[css]: https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png
