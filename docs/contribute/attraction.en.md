---
Description: This is how you edit a new attraction.
icon: material/train-car
---

# Edit attractions

Once a leisure facility has been created, you can not only assign [areas (zones) in the park](./park.md/#park-zones) to it, but also create and assign attractions.

## Basic data

### Attraction name

!!! info ""
     Give the official name (in local language) for the attraction.

### Category

!!! info ""
     Select the [Overview](./categories.md) category of the attraction. For an easier overview, we have stored the categories separately in this documentation.

### Status

!!! info ""
     We define the following states of an attraction[^1]:

     | Status|Description|
     |-----------|--------------|
     | `Under construction`| Currently under construction/conversion|
     | `In operation`| Regular operation|
     | `Former`| Attraction no longer in operation|
     | `Out of service`| Temporary, out of service for an extended period|

### Manufacturer

!!! info ""
     We keep a list of manufacturers in our database. To ensure our data quality, we add the names of the manufacturers ourselves. Select the manufacturer from the list. The search suggests corresponding names from 3 characters. The manufacturer of the attraction is the main criterion. If another manufacturer was included at a later time, you can add it.

     **Example**:
     
     [Fort Fun - SpeedSnake FREE](https://coaster.cloud/attractions/1a2a0802-speedsnake-free){:target='blank' } (built 1981) :material-arrow-right-box:{.golden} After 37 years, the train from the manufacturer [Vekoma](https://coaster.cloud/manufacturers/3bc7392a-vekoma){:target='blank' } was replaced in 2018 by a new train from the manufacturer [SunKid](https://coaster.cloud/manufacturers/41c4f014-sunkid-heege-gmbh){:target='_blank'} in 2019. Now the two manufacturers are marked here.

### Theme area (Park zone)

!!! info ""
     The zones of a leisure facility must be created in advance. Then the attraction can be linked to it. The linked attractions of a common zone are displayed in the view of the leisure facility in an overview of the park areas. In this way, you can quickly access the filter of a zone.

### Onride Video

!!! info ""
     There are many beautiful onride videos for the attractions on :simple-youtube:{.red .heartbeat} YouTube. Can you find the right one for our platform? Then copy the codes of the video into the field. Example: https://www.youtube.com/watch?v={==wNs6oRhObc8==}

### Coordinates

!!! info ""
     In order to display the facility on our map and measure distances, we need the coordinates. Please enter the **latitude** and **longitude** as decimal values. You are also welcome to compare this function with the [description for a recreational facility](./park.md#coordinates).

### Scoring System

!!! info ""
     If the attraction offers a scoring system in which you can measure yourself, then you have the options 'score' or 'time measurement' here. With every ride that you 'score', the score is now queried and archived.

## Short description

!!! info ""
     Provide a stylish short description of the attraction. Please do not copy Wikipedia texts or marketing texts. Point out what makes it special.

## Safety regulations

!!! info ""
     A very important piece of information, especially for families with children, is the safety regulations on attractions. Very often, parents ask themselves "Which roller coaster is my child allowed to ride? With our app and the collection of this data, we create an excellent overview.

     Please enter the data for minimum size, minimum age, maximum size and maximum age for 'unaccompanied' and also 'accompanied'. If the attraction has no safety regulations, set the switch to this option. This makes it clear in the evaluation that this does not matter.

## Technical information

!!! info ""
     Some technical information can be **verified** through press releases, at the attraction or other sources. So that we can have more than just a joke for the statistics, we collect this data. Of course, this also results in other parameters for e.g. 'distance ridden' and the like. Please make sure that no 'fantasy' data is created or guesses are entered!

     Especially valuable is information on length, height, maximum speed and duration of the attraction.

## Train information

!!! info ""
     We also collect information on the trains of an attraction. How many wagons per train, rows per wagon or number of trains are available? For water ride attractions, of course, the numbers for a boat. The [restraint system](../faq/restraint.md) and the seat type play another role.

## Additional information

!!! info ""
     We also collect secondary information about attractions. This allows us to filter specifically for them in the app and provide our users with a convenient app. We collect data on the area, construction costs, but also on simple attributes such as existing pre-show, accessibility, type of roofing. Some attributes are particularly interesting for special functions of the app. In the operating period, we determine whether an attraction is a classic "Halloween" attraction and can only be used during this time. This then gets its own function in the app.
     Information is also important, such as: Surcharge obligation, FastPass, Single Rider, Test Seat, Baby Switch or backpack handling.

## Elements

!!! info ""
     When we started programming our app, we thought very enthusiastically how great it would be to be able to determine the driving elements in a very detailed way. This has resulted in a very extensive list of elements. However, after the first 2 years of releases, we notice that the definition of these elements is not clear to everyone. We therefore store the [definition of the driving elements](../faq/elements.md) separately.

## History

!!! info ""
     The history of an attraction shows the changes. This is about the opening, renaming or even closing of the attraction. But beware of discussions. We have two good examples to explain why a renaming **and** a thematic change does not necessarily have to lead to a new `count`.

     **Example** - [Movie Park Germany - Show: Crazy Cops New York](https://coaster.cloud/de/attractions/8b134039-crazy-cops-new-york-das-chamaleon){:target='_blank'}
    
     This show changed its title a few times over the years and also adapted the performance slightly from year to year. At first, however, one could not speak of a "new show". For {==2023==} the show set was completely demolished and a new show starts. This is worth a new record, even if the characteristics of the venue have not changed.

     **Other example** - [Movie Park Germany - Roxy 4D Theater](https://coaster.cloud/de/attractions/2695adf5-roxy-4d){:target='_blank'}
     
     The Roxy 4D Cinema continuously offers the same experience of exciting 4D action films. The venue and the concept do not change. Only the film itself is not a reason for us to create a new record of an attraction.

[^1]: Operating an attraction: Applies to this park. If the attraction is sold, for example, it is no longer available in this park. It is like a demolition. The attraction is thus moved to the archive and can still be found under 'Former attractions'. In our search, the archived results are prioritised less in the order, if necessary.
