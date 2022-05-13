# Module 1 Challenge - Christian Kaikai


## Acceptance Criteria Checklist

- Sematic HTML elements 
- Elements follow a logical structure independent of styling and positioning
- Accessible alt attributes in img tags
- Heading attributes fall in sequential order
- Descriptive title


[View depolyed project here](https://https://github.com/ckaikai19/purple)

---

## Mockup
![website mockup](Develop/assets/images/screenshot.png)

---

## Sample Code

```html
    <!-- Every div tag in the class content has been switched to a section tag-->
    <section class="content">
        
        <section class="search-engine-optimization">
            <!-- added alt tag to img -->
            <img src="./assets/images/search-engine-optimization.jpg" alt="desk with a notbook, computer and pencils"class="float-left" />
            <h2>Search Engine Optimization</h2>
            
            <!-- <p> tag has been switched to figcaption -->
            <figcaption>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </figcaption>

        </section>
        
        <section id="online-reputation-management" class="online-reputation-management">
            <!-- added alt tag to img -->
            <img src="./assets/images/online-reputation-management.jpg" alt="desk with laptop"class="float-right" />
            <h2>Online Reputation Management</h2>

            <!-- <p> tag has been switched to figcaption -->
            <figcaption>
                The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
            </figcaption>

        </section>
       
        <section id="social-media-marketing" class="social-media-marketing">
            <!-- added alt tag to img -->
            <img src="./assets/images/social-media-marketing.jpg" alt="desk with people and computers"class="float-left" />
            <h2>Social Media Marketing</h2>

            <!-- <p> tag has been switched to figcaption -->

            <figcaption>
                Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
            </figcaption>

        </section>


    </section>
```