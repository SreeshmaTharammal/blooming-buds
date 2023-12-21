
Attachment Manual testing overview.pdf added.None selected 


Skip to content
Using Gmail with screen readers

Conversations
10.67 GB of 15 GB (71%) used
Terms · Privacy · Program Policies
Last account activity: 13 minutes ago
Details
blooming buds
# TESTING



## Responsiveness


+ The website was checked by devtools implemented in Chrome browsers.

    ## Galaxy S9:

    ![Gallery S9](documentation/galaxy_s9_responsive.png)
    
    ## Galaxy S20 Ultra:

    ![Gallery S20](documentation/galaxy_s20_ultra_responsive.png)

    ## IPad Pro:

    ![IPad Pro](documentation/ipad_pro_responsive.png)

    ## IPhone X:

    ![IPhone X](documentation/iphone_x_responsive.png)

    ## Laptop 1024:

    ![IPhone X](documentation/laptop_1024_responsive.png)

    ## Laptop 1440:

    ![IPhone X](documentation/laptop_1440_responsive.png)

    ## Laptop 2560:

    ![IPhone X](documentation/laptop_2560_responsive.png)

+ The website was checked with [Responsive Website Design Tester](https://responsivedesignchecker.com/).

    ## Desktop Screens:
    ### Desktop 1024x600
    ![Desktop 1024x600](documentation/desktop_1024_600.gif)

    ### Desktop 1024x800
    ![Desktop 1024x800](documentation/desktop_1024_800.gif)

    ### Desktop 1366x768
    ![Desktop 1366x768](documentation/desktop_1366_768.gif)
    
    ### Desktop 1440x900
    ![Desktop 1440x900](documentation/desktop_1440_900.gif)

    ### Desktop 1600x900
    ![Desktop 1600x900](documentation/desktop_1600_900.gif)

    ### Desktop 1680x1050
    ![Desktop 1680x1050](documentation/desktop_1680_1050.gif)
    
    ### Desktop 1920x1080
    ![Desktop 1920x1080](documentation/desktop_1920_1080.gif)

    ### Desktop 1920x1200
    ![Desktop 1920x1200](documentation/desktop_1920_1200.gif)

    ## Tablet Screens:
    ### Tablet 600x960
    ![Tablet 600x960](documentation/tablet_600_960.gif)
    
    ### Tablet 768x1024
    ![Tablet 768x1024](documentation/tablet_768_1024.gif)
    
    ### Tablet 800x1280
    ![Tablet 800x1280](documentation/tablet_800_1280.gif)
    
    ### Tablet 1024x768
    ![Tablet 1024x768](documentation/tablet_1024_768.gif)
    
    ### Tablet 1366x1024
    ![Tablet 1366x1024](documentation/tablet_1366_1024.gif)


    - Mobile Screens:
    ### Mobile 320x480
    ![Mobile 320x480](documentation/mobile_320_480.gif)
    
    ### Mobile 320x568
    ![Mobile 320x568](documentation/mobile_320_568.gif)
    
    ### Mobile 360x640
    ![Mobile 360x640](documentation/mobile_360_640.gif)
    
    ### Mobile 375x667
    ![Mobile 375x667](documentation/mobile_375_667.gif)
    
    ### Mobile 384x640
    ![Mobile 384x640](documentation/mobile_384_640.gif)

    ### Mobile 411x731
    ![Mobile 411x731](documentation/mobile_411_731.gif)
    
    ### Mobile 414x736
    ![Mobile 414x736](documentation/mobile_414_736.gif)

<br>                                    | Galaxy S9 | Galaxy S20 Ultra  | IPhone X  | IPad Pro  | Desktop 1024  | Desktop 1440  | Desktop > 1200px  |
| --------                              | --------  | --------          | --------  | --------  | --------      | --------      | --------          |
| Site is <br>responsive for >= 700px   | n/a       | n/a               | n/a       | Good      | Good          | Good          | Good              |
| Site is <br>responsive for < 699px    | Good      | Good              | Good      | n/a       | n/a           | n/a           | n/a               |
<br/>
| Links / URLs work                     | Good      | Good              | Good      | Good      | Good          | Good          | Good              |
| Images work                           | Good      | Good              | Good      | Good      | Good          | Good          | Good              |
| Renders are expected                  | Good      | Good              | Good      | Good      | Good          | Good          | Good              |

## Compatibility

In order to confirm the correct functionality, responsiveness, and appearance:

+ The website was tested on the following browsers: Chrome, Edge.

    - Chrome:

    ![Chrome](documentation/browsers_chrome.gif)

    - Edge:

    ![Edge](documentation/browsers_edge.gif)

## Manual testing

| feature | action | expected result | tested | passed | comments |
| --- | --- | --- | --- | --- | --- |
| Navbar | | | | | |
| Home | Click on the "Home" link | The user is redirected to the main page | Yes | Yes | - |
| About Us | Click on the "About US" link | The user is redirected to the about us page | Yes | Yes | - |
| Gallery | Click on the "Gallery" link | The user is redirected to the gallery page | Yes | Yes | - |
| Contact Us| Click on the "Contact Us" link | The user is redirected to the contact us page | Yes | Yes | - |
| Footer | | | | | |
| Facebook icon in the footer | Click on the Facebook icon | The user is redirected to the Facebook page | Yes | Yes | - |
| Twitter icon in the footer | Click on the Twitter icon | The user is redirected to the Twitter page | Yes | Yes | - |
| YouTube icon in the footer | Click on the YouTube icon | The user is redirected to the YouTube page | Yes | Yes | - |
| Instagram icon in the footer | Click on the Instagram icon | The user is redirected to the Instagram page | Yes | Yes | - |
| Contact page | | | | | |
| Name input | Enter the name | The name is entered | Yes | Yes | If user doesn't enter the name, the error message appears |
| Email input | Enter the email | The email is entered | Yes | Yes | If user doesn't enter the email, the error message appears. If user enters not valid email, the error message appears |
| Phone number | Enter the email | The phone number is entered | Yes | Yes | This field is not manadatory. If phone number is entered it is validated against valid Irish number |
| Message | Enter message | The message is entered | Yes | Yes | If user doesn't enter the message, the error message appears |
| "Submit" button | Click on the "Submit" button | The user is redirected to the response page | Yes | Yes | - |
| Response page | | | | | |
| Response message |<br>  | "Thank you for contacting Blooming Buds!" message appears along with Back to Home button  | Yes | Yes | - |
| Back to Home button | Click on Back to Home button | The user is redirected to the home page | Yes | Yes | - |


---
## Validator testing
+ ### HTML
  #### Home Page
    - No errors or warnings were found when passing through the official W3C validator.


    ![Home Page HTML Validator](documentation/w3_validator_home_page.png)

  #### About Us Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Contact Page HTML Validator](documentation/w3_validator_about_us_page.png)
    
  #### Gallery Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Gallery Page HTML Validator](documentation/w3_validator_gallery_page.png)

  #### Contact Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Contact Page HTML Validator](documentation/w3_validator_contact_us_page.png)

  #### Response Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Response Page HTML Validator](documentation/w3_validator_contact_recieve_page.png)
    
+ ### CSS
  No errors or warnings were found when passing through the official W3C (Jigsaw) validator except: 
    - One warning regarding import statement  "Imported style sheets are not checked in direct input and file upload modes"
    
  ![CSS Validator Results](documentation/w3_validator_css_results.png)


+ ## LightHouse report

    - Using lighthouse in devtools I confirmed that the website is performing well, accessible and colors and fonts chosen are readable.
    
  ### Home page

  ![Home Page Lighthouse](documentation/lighthouse_home_page.png)

  ### Gallery page

  ![Gallery Page Lighthouse](documentation/lighthouse_gallery_page.png)

  ### Contact page

  ![Contact Page Lighthouse](documentation/lighthouse_contact_us_page.png)

  ### Response page

  ![Response Page Lighthouse](documentation/lighthouse_contact_receive_page.png)

---
​
## Bugs
+ ### Solved bugs
    1. Flickering in gallery page when mouse hover feature added
    
        *Solutions:* Padding applied to fix this issue.
    
    2. About us page hero image was not showing in edge browser.
        
        *Solution:* Converted image to JPEG format. 
    
    ---
+ ### Unsolved bugs
    - None.
+ ### Mistakes
    - While updating readme used mp4 files and html tags. The vscode preview showing expected behaviour
    - Reliazed github markdown does not support this. Converted to GIF.

---