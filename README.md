# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
clone the github repository in to the theia IDE
### Step 2:
create a new django project
### Step 3:
write the needed html code

### Step 4:
run the django server and execute the html files
## Code:
```
map.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>nanganallur</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>varsha s(212222220055)</b></font>
</h3>
<center>
<img src="/static/images/map.png" usemap="#MyCity" height="420" width="1100">
<map name="MyCity">
<area shape="circle" coords="190,50,20" href="/static/html/ghs.html" title="chennai international airport">
<area shape="rectangle" coords="230,30,260,60" href="/static/html/rto.html" title="nanganallur anjaneyar temple">
<area shape="circle" coords="400,350,50" href="/static/html/vk.html" title="palavanthangal railway station">
<area shape="circle" coords="400,200,75" href="/static/html/bus.html" title="trident hotel">
<area shape="rectangle" coords="490,150,870,320" href="/static/html/park.html" title="GRT jewellers">
</map>
</center>
</body>
</html>

airport.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>airport</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>nanganallur</b></font>
</h1>
<h3 align="center">
<font color="blue"><b> chennaiairport</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
<b>
Chennai International Airport (IATA: MAA, ICAO: VOMM) is an international airport serving the city of Chennai, Tamil Nadu and its metropolitan area. It is located in Tirusulam, around 20 km (12 mi) southwest of the city centre. The airport is the 5th busiest airport in India It was also 49th busiest airport in Asia in 2018 making it one of the four major airports in India under the top 50 list of 2018.[4] In financial year 2022-23, the airport handled over 18 million passengers
</b>
</font>
</p>
</body>
</html>

grt.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>vGRT jewellers</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>nanganallur</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>GRT jewellers</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">

<ol type="1">
GRT Jewellers in Nanganallur, Chennai is a recognised name in the city since 2017. With rich experience in the gems and jewellery business, this firm has become a celebrated name for stunning designs and collections.
Pay for the product or service with ease by using any of the available modes of payment, such as Cash, Master Card, Visa Card, Debit Cards, American Express Card, Credit Card. 
</ol>
</font>
</p>
</body>
</html>


hotel.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>trident hotel</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="red"><b>nanganallur</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>trident hotel</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">

<ul>
Trident, Chennai is near Chennai airport (just 3 kilometres away) and 12 kilometres from the railway station. The hotel is also located near to the new business districts of the city of Oragadam, Mahindra World City, Maraimalai Nagar and Guindy. It is only a 10 minute drive from the Chennai Trade Centre. Trident, Chennai is also perfectly positioned to enjoy the city's famous sights and five star attractions. The hotel concierge can help arrange city tours or suggest the best places to shop for souvenirs.
</ul>
</font>
</p>
</body>
</html>


railway.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>palavanthangal railway station</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>nanganallur</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>palavanthangal railway station</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
Pazhavanthangal railway station is one of the railway stations of the Chennai Beach–Chengelpet section of the Chennai Suburban Railway Network. It serves the neighbourhood of Pazhavanthangal and surrounding areas. It is situated about 18 km (11 mi) from Chennai Beach, and has an elevation of 12 m (39 ft) above sea level. 
</font>
</p>
</body>
</html>

temple.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>nanganallur anjaneyar temple</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>nanganallur</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>nanganallur anjaneyar temple</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Arial" size="5">
<b>
The Anjaneya Temple at Nanganallur, Chennai is a Hindu temple dedicated to the god Hanuman. The principal idol of Hanuman is 32 feet tall and sculpted from a single piece of granite, which the second tallest Hanuman after Panchavatee near Puducherry. The idol was installed in 1989 and consecrated in 1995.The temple is now under the custody of HR & CE It was taken by HR & CE in 2008. This action was severely criticized by Sri Maruthi Bhaktha Samajam Trust, the former management.
</b>
</font>
</p>
</body>
</html>
```
## Output:
![output](./out1.png)

![output](./out2.png)
![output](./out3.png)
![output](./out4.png)
![output](./out5.png)
![output](./out6.png)
## html validator
![HTML Validator](./valid.png)

## Result:
The program for implementing image map is executed successfully