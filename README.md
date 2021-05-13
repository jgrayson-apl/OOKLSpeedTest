# OOKLA Speed Test
 
Collect information about connection speeds including location and user provided details via Survey123 and use OOKLA to automatically measure speeds.   

## Demo
[Community Speed Test Survey](https://apl.bd.esri.com/SpeedTest/index.html)

## Technologies Used

### Esri Survey123
- [Blog: Introducing the Survey123 Web App JavaScript API](https://community.esri.com/t5/arcgis-survey123-blog/introducing-the-survey123-web-app-javascript-api/ba-p/896667)
- [Survey123WebFormOptions](https://developers.arcgis.com/survey123/api-reference/web-app/Survey123WebFormOptions)

### OOKLA
- [Embed Your Test on Your Website](https://support.ookla.com/hc/en-us/articles/115003370267-Embed-Your-Test-on-Your-Website)
- [Hosting the HTML5 front-end Test UI on your site](https://support.ookla.com/hc/en-us/articles/115001660712-Hosting-the-HTML5-front-end-Test-UI-on-your-site)
- [Passing Test Results To The Browser](https://support.ookla.com/hc/en-us/articles/115005319507-Passing-Test-Results-To-The-Browser)
- [Storing STC results using Javascript](https://support.ookla.com/hc/en-us/articles/360000725112)

## Deploy

This demo is built as a static web application.

1 - Download and copy the root folder to a web accessible location\
2 - Update the configuration parameters in ./config/application.json 

## Configure

Update the [application.json](https://github.com/jgrayson-apl/OOKLSpeedTest/blob/master/config/application.json) file in your favorite json editor:

| parameter | details |
| ---: | --- |
| **portalUrl** | Organization or Enterprise URL; example: https://www.arcgis.com |
| **clientId**  | The client ID is a string that proves that you have explicitly authorized the use of Survey123 web app API from your web page. You need to create the Client ID through the https://developers.arcgis.com/ website. |
| **itemId**    | This is the ArcGIS itemID of your web form. |
| **ooklaUrl**  | This is the custom OOKLA test url you've configured at https://account.speedtestcustom.com/login |

## TODO
- no OAuth authentication implemented.

### Contact
> [jgrayson@esri.com](mailto:jgrayson@esri.com?subject=OOKLASpeedTest&body=I%20have%20a%20quesiton%20about%20the%20OOKLAvSpeed%20Test%20app)\
> Geo Experience Center, Esri\
> _April 2021_
