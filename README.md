# Adopt Don't Shop: A Look into Crowded Animal Shelters in America and Why You Should Adopt.

Capstone Project for Full-time Data Analytics Cohort #7 program at Nashville Software School

## Contents

- [The Motivation](#The-Motivation)
- [The Question](#The-Question)
- [The Dream](#The-Dream)
- [The Reality](#The-Reality)
- [The Data](#The-Data)
- [The Technology](#The-Technology)
- [The Process](#The-Process)
- [The Product](#The-Product)

## The Motivation
  
Growing up in Brazil, my dogs and cats’ friends were always mutts, I would find them on the streets, and I would bring them home and I would bring my most sad face and the most incredible compelling pitch in hope that my mom would allow me to keep them and on many occasions she did. Despite knowing that going to the vet for checkups is important for you and your pet, my childhood doggies and cats never saw a vet and they lived furrever.

However, when I moved to US and I was able to afford a pet, everyone would tell me to look for a breeder with AKC registration and that paying the price up front would allow me to have a healthy dog later, so I believed on the idea. After purchasing two Rottweiler from a back yard breeder for $500 a pop, my furry kids grew up with a lot of joint and health problems. The issues included 3 joint surgeries, constant allergies, skin, and ear infections, bone cancer, hip dysplasia, and painful arthritis, combined with endless vet bills and medications. I loved my dogs, and I would do it all over again, however I discovery a much cheaper, sustainable, and still very loveable way to find my furry friend…SHELTERS!!!

There so many mistreated animals and a lot of overbreeding pets that leads to major health concerns when they grow up. Puppy mills are a big business in this country, where especially dogs are bred in very poor conditions leading to unhealthy puppies and a very short and painful lifespan for the mothers. Also, there are so many great companions in shelters that in many cases they are euthanized because of the lack of space, resources, and not enough adoptions.


## The Question

Why adopt a pet if you can easily buy one?

What kind of pets are available for adoption?

## The Dream

My first approach was to research the area of Nashville or at least investigate any city or county around Metro Area. Gather all the dataset for shelters and/or animals rescues and animal humane societies near by. The reason why is because I live in this area and with this research, I could help somehow the community around me, spot trends, and help guiding the shelters to better marketing campaigns or to specific area. And I even went a step further and opened my search to the whole state of TN in case Nashville failed through.

## The Reality

I was unable to find available data for Nashville and very little for most of the cities or counties in TN. The few that I was able to find did not contain the necessary information to help me to answer my question. Emails were sent requesting the data , but no answers.
As my instructor said, you have to go where the data is… so I did, and I ended up in TX.

## The Data
This project analyze data from [Shelter Animals Count](https://www.shelteranimalscount.org/) and [Open Data Network](https://www.opendatanetwork.com/) dataset for two TX cities regarding their shelters activities.
Shelter Animals Count (SAC) dataset contains information from shelters around the US and it's divided by state and year for Felines and Canines only. The data is for the year of 2019, 2020, and 2022.
The second dataset from Open Data Network are for Austin and Dallas, TX from 2015 to 2022.

## The Technology

* Python
  * Jupyter Notebooks
  * pandas
  * datetime
  
* Power BI dashboard

## The Process

### Gather

It took me a lot of searching online for the data that I wanted to research. As mentioned above I wanted to present my project with Nashville or TN data. Most of my searchs would take me to statistics that were great but the data was already agregated so they were not useful. My instructor directed to Open Data Network and boom! I was able to find useful data to work with.
The SAC dataset was actually a friend of a friend that sent me the link. I was very happy to be able to access that data!
So I had to download multiple CSV files, especially for Dallas dataset, but I was just very excited with the findings.

### Clean & Prepare

The cleaning part of my project was the one that took me the most time and energy.

For the SAC dataset had a lot of columns with a variety of information for both felines and canines. So I had to make sense of the data and see what would help me to answer my questions the most. I had over 30 columns of information and I dialed down to only a few. Also the values in the columns had to be changed from objects to integers for better calculation. Once I had a good understanding of the data and extracted what I needed, I separated it into Felines columsna and Canine columns for better visualization and future presentation.

The dataset for Dallas and Austin I used separete notebooks, mostly because I was getting overwelmed by so many tables and I started to get lost on my own work lol. Dallas dataset was large and extensive, each year had it's own table and each table had it's own formating. This dataset took a me awhile to clean and have it ready for any type of calculation. Columns' name, values, and few NAN to clean up before I could merge all the tables in one. After renaming, changing the values to integers, drop some unuseful columns, merge, and so on I ended up with a good final table. The same had to be done for Austin dataset, a little less tables to deal with, but it also took me a lot of time cleaning the columns. Finally after days of grinding and with the help of my peers, I was able to merge Dallas and Austin dataset! 

### Launch

Once all the cleaning up was done, I started to try out what could find or if there was anything interesting outside of my questions. I had a lot of fun wiht the data and if I could I would have a much longer dashboards... But my presentation had to be 5 to 10 minutes, so I kept focused on the most important topics. I made a final notebook with all the tables I was going to use for the dashboards and from there I imported to Power BI where I started to use my creative side. I started broad with graphs and images. Then I zoomed in and tight up on the font, colors, and sizes and trying to bring together along with creating a smooth storytelling from one page to another.

## The Product

I am very grateful for this opportunity to present something that I care dearly and thanks to my instructors and teammates my vision became reality. I hope you will enjoy as much I did! 


Until the next project 

Tchau Tchau!!

[Final Product](https://app.powerbi.com/view?r=eyJrIjoiZTUwMTE0MzEtNWFlOC00OTM4LTliNTUtZTZmZjNjMDQ0ZTRiIiwidCI6IjEwMWRhNTg3LTE4NDMtNGY1Mi04YjhhLTE3YjA2OWM2NmQzMyIsImMiOjJ9)
