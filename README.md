# Ex04 Places Around Me
## Date : 22/04/2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
map.html

<html>
    <head>
       <title>CITY</title>
    </head>
    <body>
        <h1 align="center">
            <font color="blue"><b>THIRUVARUR</b></font>
        </h1>
        <h3 align="center">
        <font color="green"><b>VENKATESAN R</b></font>
        </h3>
        <CENTER>
            <img src="map.png" usemap="#MyCity" height="610" width="1450">
            <map name="MyCity">
            <area shape="rect" coords="600,250,850,400" href="home.html" title="MY HOME TOWN">
            <area shape="rect" coords="200,100,500,500" href="collage.html" title="MEDICAL COLLAGE">
            <area shape="rect" coords="1033,330,1202,404" href="thiru.html" alt="college" title="THIRU.VI.KA COLLEGE">
            <area shape="rect" coords="1129,468,1356,615" href="place.html" title="ALIVALAM">
            <area shape="rect" coords="61,486,194,564" href="kuli.html" title="KULIKARAI">
    
            </map>
        </CENTER>
    </body>
</html>

collage.html

<html>
    <BODY bgcolor="yellow">
    <h2 align="center"><font color="BLUE">THIRUVARUR</h2></FONT>
    <H3 align="center">GOVT. MEDICAL COLLAGE</H3>
    <HR>
    <p align="justify">A government medical college is an educational institution that offers medical courses and programs, such as MBBS, BDS, MD, and MS, under the direct funding and management of the government. These colleges aim to provide quality medical education and training to students at affordable tuition fees, ensuring that healthcare professionals are well-equipped to serve the community. Government medical colleges often have a long-standing reputation for excellence and are known for their experienced faculty, comprehensive curriculum, and state-of-the-art medical facilities. They play a critical role in producing skilled doctors and specialists who contribute significantly to the healthcare system. Admission to these institutions is usually highly competitive, based on entrance exams and academic performance, making them a sought-after option for aspiring medical professionals.</p>
</BODY>
</html>

home.html

<html>
    <BODY bgcolor="yellow">
    <h2 align="center"><font color="BLUE">THIRUVARUR</h2></FONT>
    <H3 align="center">HOME TOWN</H3>
    <HR>
    <p align="justify">Thiruvarur also spelt as Tiruvarur is a municipality in the Indian state of Tamil Nadu. It is the administrative headquarters of Thiruvarur district and Thiruvarur taluk. The temple chariot of the Thyagaraja temple, weighing 360 tonnes (790,000 lb) and measuring 96 feet (29 m) tall is the largest temple chariot in India. Thiruvarur is the birthplace of Tyagaraja, Muthuswami Dikshitar and Syama Sastri, popularly known as the Trinity of Carnatic music of the 18th century CE. Thiruvarur Thiyagarajaa Swaamy temple is older than Tanjore big temple.

        Thiruvarur was a part of Thanjavur district until 1991. The Odambokki river passes through the centre of the town. Thiruvarur covers an area of 10.47 km2 (4.04 sq mi) and had a population of 58,301 as of 2011. Out of total population of Tiruvarur, 1,403,348 in the district, 257,795 are in urban area and 1,006,482 are in rural area. 65,220 households are in urban, 261,999 are in rural area. It is administered by a selection grade municipality. The town is a part of the Cauvery delta region and agriculture is the major occupation. Roadways are the major means of transportation with a total of 94.06 km (58.45 mi) of district roads including three national highways passing through the town. The town was one of the five traditional capitals of the Chola empire, with one of the emperors of the dynasty, Kulothunga Chola I, having it as his capital. The town is believed to be of significant antiquity and has been ruled, at different times, by the Medieval Cholas, Later Cholas, Later Pandyas, Vijayanagar Empire, Thanjavur Nayaks, Marathas and the British. The town is known for the Thyagaraja temple, and the annual Asian biggest chariot festival held in the month of April.</p>
</BODY>
</html>

kuli.html

<html>
    <BODY bgcolor="yellow">
    <h2 align="center"><font color="BLUE">THIRUVARUR</h2></FONT>
    <H3 align="center">KULIKARAI</H3>
    <HR>
    <p align="justify">Kulikkarai is a small village located in the Thiruvarur district of Tamil Nadu, falling under the Koradacheri block. It is situated approximately 6 to 7 kilometers west of the district headquarters, Thiruvarur. Known for its peaceful rural setting, Kulikkarai is part of the Peruntharakudi Gram Panchayat and is home to a population of around 2,000 people, as per the 2011 census. The village maintains a good literacy rate, with both men and women actively participating in education. Kulikkarai is well connected by road and rail, with its own railway station (code: KU) that provides easy access to nearby towns and cities. The village reflects the cultural and traditional essence of Tamil Nadu, with agriculture being the primary occupation of the residents.</p>
</BODY>
</html>

place.html

<html>
    <BODY bgcolor="yellow">
    <h2 align="center"><font color="BLUE">THIRUVARUR</h2></FONT>
    <H3 align="center">ALIVALAM</H3>
    <HR>
    <p align="justify">Thiruvarur is a culturally rich district located in the southern part of Tamil Nadu. Known for its deep spiritual roots and classical music heritage, Thiruvarur holds a special place in the history of South India. The district is home to the famous Thyagaraja Temple, a grand architectural marvel dedicated to Lord Shiva, which also hosts one of the largest temple chariots in Asia. Thiruvarur is the birthplace of the great Carnatic music composer Saint Thyagaraja, making it a significant center for traditional South Indian music. Apart from its cultural importance, Thiruvarur is also an agricultural hub, with fertile lands supported by the Cauvery river system, making it ideal for paddy cultivation. The district's vibrant festivals, temples, and historical legacy continue to attract devotees, tourists, and music lovers from all parts of the country</p>
</BODY>
</html>

thiru.html

<html>
    <BODY bgcolor="yellow">
    <h2 align="center"><font color="BLUE">THIRUVARUR</h2></FONT>
    <H3 align="center">THIRU.VI.KA.COLLAGE</H3>
    <HR>
    <p align="justify">An Arts and Science college is an educational institution that offers a broad range of undergraduate and postgraduate programs in the fields of arts, sciences, and humanities. These colleges typically provide courses in subjects like literature, history, philosophy, psychology, mathematics, physics, chemistry, biology, and other natural or social sciences. The aim of an Arts and Science college is to offer a well-rounded education that fosters intellectual growth, critical thinking, and creativity across diverse disciplines.

        In an Arts and Science college, students can choose from various specializations depending on their interests, and the courses are designed to prepare them for a variety of careers in education, research, industry, government, and more. The curriculum often emphasizes both theoretical knowledge and practical application, with students engaging in laboratory work, field studies, research projects, and internships. These colleges are essential in shaping well-educated individuals capable of contributing to societal development, innovation, and cultural enrichment.
        
        Such institutions often maintain a focus on holistic development by encouraging extracurricular activities, arts, sports, and cultural events, providing a comprehensive learning experience for students.</p>
</BODY>
</html>
```

## OUTPUT
![Screenshot (15)](https://github.com/user-attachments/assets/e121ccb4-6e20-4522-97d5-3c5cdd1f94e4)
![alt text](<venkat/Screenshot (16).png>)
![alt text](<venkat/Screenshot (17).png>)
![alt text](<venkat/Screenshot (18).png>)
![alt text](<venkat/Screenshot (19).png>)
![alt text](<venkat/Screenshot (20).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
