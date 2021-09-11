<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a >
    // add image logo ya finsys to image file with the name logo.png and delete this line from the readMe<br>
    <img src="images/logo.png" alt="Logo" width="280" height="180">
  </a>


  <h3 align="center">Cisco Innovation Challenge </h3>
  

## Setup/ Installation
### 1.Set up WebApp
1. Copy the project to  your web server root eg _var/www in the case of _apache
2. Run composer install
3. Edit environmentConfig.php file of the prodject accordingly and set project constants as required.
4. Start the webserver and view the app on the browser.


## Feature Modules
1. ## Overview module
    This module shows brief data of the organization action logs of that day. Data shown on this module can include the spending metrics on calls on that day as well as a graph of outgoing vs incoming calls. Other data available is a tabular format of the top callers( individuals with the most calls)
2. ## Reports
This module delves deeper in the data on overview module providing more and finer 
details. The reports are classified into sub categories namely calls,employee,Department and exetension. 

3. ## Analysis
This module provides insigt into the stats that come for the data collected. Basically transform rows of data into meaningful inormation that the management can use to make  informed decisions.

4.  ##  Settings
This module enables an organization to fully cutomize and adopt the system into their day to day work. Using this module the admin of the organization is able to set up data for the organization such as : <br>
         * Call tariffs rates for different service providers
         * Setting up new users and extensions 
         * Edit users to departments 
         
5.  ## Scheduler
Usig the scheduler the admin can set up the frequency of reports to be sent to his or any email. One can also specify the type of data to be be periodically generated and specify the emails to receive the data.



## Frameworks used
* Code Ignitor Framework 
* Vue JS

## Technologies
* MVC 
* Rest APIs

## Project Archicture

### Thin Client-Fat server 
A server which runs an application where most of the program code resides on it rather than on the client computers. A good example of this type of server is a Web server, where the code for responding to requests from a browser resides on the server. Fat servers are normally associated with thin clients. Fat servers and thin clients have the advantage that software updates to the service are easy to carry out: all that needs to be changed is the code on the server, not the code on the many clients that might access the server



## Credits
1. [Cyrus Muchiri](https://github.com/Cyrus-Muchiri) 
2. [Mwaura Gitonga](https://github.com/mwauragitonga)
3. [Stanley Mandela](https://github.com/StanMandela)


<!-- LICENSE -->
## License

Distributed under the [MIT License](LICENSE).  for more information.

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Pages](https://pages.github.com)

