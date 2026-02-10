#  Specification Phase Exercise

A little exercise to get started with the specification phase of the software development lifecycle. See the [instructions](instructions.md) for more detail.

## APP name 
Campus Bites

## Team members


[Ethan Demol](https://github.com/ethandemol) <br>
[Kyle Chen](https://github.com/KyleC55)<br>
[Angelina Wu](github.com/TangelinaWu)<br>
[Zheqi Zhang](https://github.com/zheqi111)<br>
[Karen Maza Delgado](https://github.com/KarenMazaDelgado)<br>
[]()<br>
[]()<br>


## Stakeholders


Primary Users- NYU Students, Restaurants

### Charlie Burke - NYU Student<br>
Budget-Constrained Commuter Student

**Student Goals**<br>
- Find affordable meals within his student budget
- Access consistent and reliable student discounts for everyday meals.
- Avoid overspending due to lack of clear pricing information.

**Student Problem**<br>
- Primarily discovering discounts through street signage or verbally, which is inconvenient and unreliable.
- Discount information is often not clearly advertised, including confusing restrictions, time limits, and eligibility rules.
- Current apps on the market like Too Good To Go do not fit his habitual needs having time crunches and only specials.

### Noelia Yang - NYU Student<br>
Overloaded Academic Students

**Student Goals**<br>
- Loves a good deal but wants convenient food options primarily to save time.
- Wants to quickly identify options near her that she can integrate into her daily routine.
- Needs to be close or she would rather waste money at the closest restaurants even if the price hurts.

**Student Problem**<br>
- After class, even if she knows a deal is there, because of convenience she would get something nearby, wasting money.
- Does not actively search for discounts, however would integrate it in their life if it was easier.
- Wants deals on certain paths between classes and doesn't want to deviate too much from her original daily paths.



### Benito Ramirez - NYU Student<br>
Exploratory Social Eater

**Student Goals**<br>
- Loves trying new food around him with friends.
- Discover good food worth the price, fit for different occasions (grab and go, sit down, coffee shops, etc.)
- Loves a good deal but will not sacrifice taste.

**Student Problem**<br>
- Current deals are not well displayed, leading him to often eat at restaurants without realizing they even had deals.
- Cannot find hidden gems leading him to default the same few restaurants; he is getting bored.



### Jessia Alba - NYU Student<br>
Health focused Student Athlete

**Student Goals**<br>
- Wants to locate healthy discounted food that is good for her performance.
- Avoid snacks and processed goods, focusing on natural options that don't break her wallet.

**Student Problem**<br>
- Limited discount visibility on nutritional options leading to her missing opportunities.
- Few healthy discounts she can find, leading her to just order CAVA daily.



### Andrew Chacon - NYU Student<br>
Discount Hunter

**Student Goals**<br>
- Secure significant discounts (40-50%) even if it requires a 20-minute walk.
- Find "Mystery Bag" style deals to get a variety of food at a lower price point.
- Save money on daily meals to support a very frequent deal-based eating habit.

**Student Problem**<br>
- High social friction and embarrassment when having to verbally ask staff if a discount exists.
- Low visibility of deals, currently relying on physically walking past stores to spot NYU banners.
- Frequent disappointment with the actual "discounted" price not being low enough.



### Samuel Zheng - GCSU Student<br>
Budget Conscious

**Student Goals**<br>
- Find restaurants near campus through social media and through classmates.
- Mostly go to staple areas/restaurants, and only try somewhere new about 10% of the time.
- Only choose places that are within about a 30 minute walk.

**Student Problem**<br>
- When restaurants offer a student discount, he doesn’t make much note of the actual price because competition makes prices feel similar.
- He has never used these services before.
- The biggest friction point is telling the cashier you’re trying to use a discount.


### Hashi Market<br>
**Restuarant Goals** <br>
- Reduce end-of-day food waste while maintaining operational efficiency.
- Attract more NYU students using existing student discounts and end-of-day promotions.
- Leverage multiple locations and a strong social media presence to increase student awareness.
- Maintain fast service without adding operational complexity.

**Restaurant Problem**<br>
- Discounts are applied manually, which is time-consuming and difficult to scale during busy periods.
- Lack of automation makes it difficult to quickly adjust or toggle discounts on and off.
- Staffing and hiring challenges create operational strain, indirectly impacting waste reduction efforts.

### Tartinery<br>
**Restuarant Goals** <br>
- Attract NYU students during weekday daytime hours when foot traffic is lower.
- Maintain consistently low food waste levels.
- Continue offering a simple, standard student discount without changing existing workflows.

**Restaurant Problem**<br>
- Many students are unaware that a 10% NYU student discount exists.
- Staff often need to ask customers whether they are students to apply the discount, which is inefficient and inconsistent.
- Limited incentive to expand or modify discount offerings due to already low food waste.

### Tandon Deli<br>
**Restaurant Goals**<br>
- Increase student foot traffic and become a primary lunch destination for the Tandon campus.
- Maintain high-speed service for students rushing between classes.
- Capitalize on their convenient location to capture more consistent daily revenue from the local NYU community.

**Restaurant Problem**<br>
- High price points create a barrier to entry for budget-conscious students.
- Low motivation to implement complex discount systems; as a high-volume deli, they prioritize transaction speed over marketing.
- Lack of a clear value proposition or loyalty incentive, making students view them as a last resort.


### Suki r<br>
Restaurant Owner<br>

**Restaurant Goals**<br>
- Promote student deals through flyers and advertising through social media.
- Keep daily prepared food waste low.
- Track sales at the end of the day through the existing ordering app.
- Use a simple verification method and student ID is comfortable enough.

**Restaurant Problem**<br>
- Student discounts may reduce normal profits, and normal customers might be turned away by long lines caused by students.
- Biggest hurdle: students may wait until the last hour to order food, making it harder to close and clean on time.
- The restaurant already has a reliable ordering system app.


### Overview<br>

From our interviews, we realized we needed to pivot from our original idea of a real-time, item-specific discounting system (where both students and restaurants would be active users) to a simpler, student-focused application that clearly displays existing student discounts at nearby restaurants (e.g 10% off at Tartinery). 

This was for two reasons. Firstly, many restaurants near NYU have little to no food waste and the restaurants that do have any waste already use platforms such as TooGoodToGo. The second reason was that many students wanted predictability and clarity. They don't want specific item discounts and they want to have a bit more clarity going into the day where they can get a good deal near Bobst rather than have to wait for sporadic notifications. 

As a result, our primary and sole user is now the NYU student, and the application is designed to help them quickly and easily discover nearby student discounts.

**Goals**<br>
1. Quickly find student discounts near campus.
2. Save money on everyday meals.
3. Minimize time spent deciding where to eat.
4. Discover new restaurants close to campus.

**Frustrations**<br>
1. Lack of centralized information about discounts.
2. Awkwardness of asking for discounts in person.
3. Over-reliance on familiar food spots.
4. Dislike of unpredictable or pre-payment discount models such as TooGoodToGo.

## Product Vision Statement

A mobile app that helps NYU students quickly discover nearby restaurants offering student discounts, view the discount details, and navigate to the best option based on distance and preference.

## User Requirements
1. As an NYU student, I want to see nearby restaurants that offer student discounts so that I can save money on meals.
2. As an NYU student, I want to quickly find the nearest discount around Bobst so that I can save time deciding where to eat.
3. As an NYU student, I want to view discount details before going to a restaurant so that I know exactly what I’m getting.
4. As an NYU student, I want to see specific discounted items rather than mystery offers so that I can choose food I actually want.
5. As an NYU student, I want discounts to be clearly labeled as student discounts so that I don’t feel awkward asking at the register.
6. As an NYU student, I want to filter restaurants by distance so that I don’t have to walk too far for a deal.
7. As an NYU student, I want to filter discounts by time of day so that I can find deals that fit into my schedule.
8. As an NYU student, I want to discover new restaurants near campus so that I don’t always eat at the same places.
9. As an NYU student, I want the app to show only restaurants near campus so that the information feels relevant and useful.
10. As an NYU student, I want the app to be simple and fast to use so that finding a discount doesn’t feel like extra work.
11. As an NYU student, I want to reserve or order discounted and promotional items, including coupons, so I can secure the deal and pick up my order later before the items sell out.
12. As an NYU student, I want to view nearby restaurants and markets that offer discounts or special deals on specific food items, so I can quickly choose a convenient location and know exactly what I am purchasing before pickup.

## Activity Diagrams
**User Story:**  
As a student user, I want to reserve or order discounted and promotional items, including coupons, so I can secure the deal and pick up my order later before the items sell out.

![UML Activity Diagram - Order for Pickup](images/Diagram1.png)

## UML Activity Diagram 2 . Nearby Discounts

**User Story:**  
As a student user, I want to view nearby restaurants and markets that offer discounts or special deals on specific food items, so I can quickly choose a convenient location and know exactly what I am purchasing before pickup.

![UML Activity Diagram - Nearby Discounts](images/Diagram2.png)

## Clickable Prototype

**[Clickable Prototype](https://www.figma.com/proto/JxEQS6iTELe9u8KcojCFyC/Otters---Wireframe---Prototype?node-id=23-3&p=f&t=4Mx8STc7zvDBF5pH-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=23%3A3):** <br>
Link To Prototype: 
https://www.figma.com/proto/JxEQS6iTELe9u8KcojCFyC/Otters---Wireframe---Prototype?node-id=23-3&p=f&t=4Mx8STc7zvDBF5pH-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=23%3A3
