[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/isPhTOcA)

# Iman Maris-Weekly Assignments - Week 4 

## Weekly Assignments - Week 4
Contains about the weekly tasks of the revou course has a goal to learn some new knowledge about software engineering. The fourth week's assignment contains :
1. How to deploy a website things that will built and deploy on netlify.
2. The deployment must be auto deploy from project main branch using github.
3. Custom domain must be connected
4. Documented the steps and process on a readme 

---
## About my Website
I'm newbie about this but i will try to create a my personal website assignment. The topic of my website contains about sales of spices and other things related to herbs.

### Website Layout
My website layout consists of :

 * `Navigasi bar`
 * `Heading`
 * `Main` yang berisi `display`, `list picture`, `how to use`, and `form address`
 * `footer`

### Usage
The main files and directories in the project can you customize,
 * `index.html`
 * `style.css`

your suggestions, feedback and input are very useful for my knowledge about this..

---

## Documentation of Stages and Processes 
Contains the stages of the process from start to finish

### About Buy Domain  
Domain purchase at Niagahoster, following are the steps for the purchase..

* Open website [niagahoster](https://www.niagahoster.co.id/domain-murah)
* Check the desired domain name, is it still available? If still available, then press "pilih"
  ![check desire domain](/image%20readme/image.png)
###
* Checklist the added domain names and continue.
  ![checklist and select buyer methode](/image%20readme/image-1.png)
###
* If you haven't logged into Niagahoster, you can log in or register first
  ![login first](/image%20readme/image-2.png)
###
* If already logged in, the menu will return to the payment method display. Can directly select Checkout now
  ![checkout after login](/image%20readme/image-3.png)
###
* Complete your personal data to continue payment and select agree "setuju"
  ![completed personal data](/image%20readme/image-4.png)
###
* Next will come out the total purchase invoice
  ![purchase invoice](/image%20readme/image-5.png)
###
* After making a payment, wait until the payment is verified
  ![payment is verified](/image%20readme/image-6.png)

---
### Deployment Process
#### Prepare File and Push to Github

Before going on to the steps for deploying a static website to netlify, first prepare the website files and push them to github. Then create a new repository on github to hold the files you just created.

![push process with gitbush](/image%20readme/deploy1.png)

After the html file is ready and the repository on Github has been created, now we push the file to the repository that was created on Github using the basic git command as shown above.

![after push in github](/image%20readme/deploy2.png)
-
#### Deployment Static Website with Netlify

##### Step 1: Create Account
Register or sign in first

![front display in netlify](/image%20readme/deploy3.png)

Please select a registration method to use, I will sign in using GitHub

![sign in with github](/image%20readme/deploy4.png)

After success, you will be redirected to the Netlify dashboard.

![after sucsess sign in with github](/image%20readme/deploy5.png)

--
##### Step 2: Add a New Project
Then it will be redirected to an overview page as shown below. Please click the "add new site" button then select "import an existing project"

![add new site with github](/image%20readme/deploy6.png)

In this second step, please click the button "deploy with github"

![deploy  with github](/image%20readme/deploy7.png)

--
##### Step 3: Authorized
After selecting github, wait for the authorization process

![next step is authorized](/image%20readme/deploy8.png)

--
##### Step 4: Select Your Repository
Next, select the repository on github that you want to deploy to the new site on netlify,

![choose account github to deploy in netlify](/image%20readme/deploy9.png)

and choose your project to deploy.

![choose project to deploy](/image%20readme/deploy10.png)

--
##### Step 5: Configure
Then in the configuration or site setting step, please adjust it to your website's source code.

![cofigure process](/image%20readme/deploy11.png)

After clicking Deploy Site, wait until the deploy process is complete. If the deploy process is complete, the static website can be accessed.

![done access](/image%20readme/deploy12.png)

--
##### Step 6: Change Site Name
Default site name from netlify can be changed by editing site name.

![domain setting to edit site name](/image%20readme/deploy13.png)

Then, edit and customize the site name you want. And click "save"

![edit and change name site](/image%20readme/deploy14.png)

Final result looks like this

![the end result looks like this](/image%20readme/deploy15.png)

---
### Connect to Domain and DNS

#### Prepare Domain and Website Static from Netlify
Before the connection process, it is necessary to prepare a paid custom domain first.

![domain custom](/image%20readme/image-6.png)

--
#### Content Delivery Network Use Cloudflare
##### Step 1: Connect to Cloudflare
Open website [Cloudflare](https://www.cloudflare.com/) and sign in there. If complete your account, can click "apply"

![sign in at cloudflare](/image%20readme/connect1.png)

Then, click "Add a website or application".

![Add a website](/image%20readme/connect2.png)

Then write down the domain name that has been prepared, and then click "add site".

![input domain in cloudflare](/image%20readme/connect3.png)

After that several service options will be provided, select free for those that are not paid. Then click "continue.

![choose free session](/image%20readme/connect4.png)

Waiting for scanning..

![scanning site in cloudflare](/image%20readme/connect5.png)

Than select "continue" and select "confirm".

![next display after choose free session](/image%20readme/connect6.png)

--
##### Step 2: Colaboration to Update Name Server
Open the Niagahoster website and log in. Then click "kelola layanan".

![update name server1](/image%20readme/connect7.png)

Next choose "Ubah Nameserver" in overview domain.

![update name server2](/image%20readme/connect8.png)

Open cloudflare and click "overview menu", then add cloudflare nameserver with copy to paste in update nameserver niagahoster. Then click "Simpan"

![paste name saver from cloudflare](/image%20readme/connect9.png)

Done, check name server. Then go to "Quick Start Guide".

![done check name server](/image%20readme/connect10.png)

Set according to the number in the instructions below. Then click "Finish"

![Setting at start guide](/image%20readme/connect11.png)

Wait for nameserver verification approximately 10 minutes, and Don't forget to log out after this.

![verificated nameserver](/image%20readme/connect12.png)

After ± 10 minutes, please log in your account on cloudflare.
If nameserver is active, marked as shown below. And click on the notification.

![nameserver active](/image%20readme/connect13.png)

--
##### Step 3: Configuration Domain to Connect Netlify
Choose type "CNAME"

![identification server](/image%20readme/connect14.png)

Then, copy your nameserver domain in netlify.

![copied nameserver netlify](/image%20readme/connect15.png)

Then, paste to "target" in cloudflare.

![paste nameserver to cloudflare](/image%20readme/connect16.png)

And add "@" to name "required" in cloudflare. Then click "save"

![input @ in name cloudflare](/image%20readme/connect17.png)

Nameservers already saved,

![already saved](/image%20readme/connect18.png)

--
##### Step 4: Finally
Contains about the end of the domain linking,
then add domain in netlify and write your domain custom name.

![add domain in netlify](/image%20readme/connect19.png)

And wait verified process, then click "add domain"

![add domain verified](/image%20readme/connect20.png)

and finally custom domain can be accessed..

![finnaly process](/image%20readme/connect21.png)

following domain name, if interested can be accessed [`here`](https://imanmaris.site/)
[imanmaris.site](https://imanmaris.site/) 

![final display from custom domain](/image%20readme/connect22.png)

---

Thanks a lot
`*copyright © 2023 Iman*`


