# Team ARES Website
Repository for the team's official website.

## Quinton's Setup Instructions
Hi there! Here are some quick instructions for how to set up the website development environment,

### Env Setup
Before we get started, **Make sure you have ["Hugo Extended"](https://github.com/gohugoio/hugo/releases) installed, not the regular Hugo version**

Once those conditions have been met, clone the repo using the following command:

```bash
git clone git@github.com:Team-ARES-Airflow-Processing-Pipeline/Website.git
```

At this point, the server should run when you execute `hugo server`

---

### Updating the Website
[Link to KB Knowledge Article](https://nau.service-now.com/now/nav/ui/classic/params/target/kb_view.do%3Fsysparm_article%3DKB0014714)

#### Windows
Use Windows File Explorer to connect to: \\arshares.ucc.nau.edu\web\ceias.nau.edu\capstone\projects\ and then navigate down under <DEPARTMENT>\<YEAR>\<GROUP-NAME>
The department abbreviation must be capitalized, for example EE, ME, CS, BIO, etc.
for example: /www/ceias.nau.edu/capstone/projects/ME/2008/Prometheus
When your web folder is selected, simply drag your web files from your local site over to the web folder.
After uploading your web documents you can view your webpage from a web browser at
http://ceias.nau.edu/capstone/projects/<DISCIPLINE>/<YEAR>/<GROUP-NAME>
or find your page on the D4P Senior Capstone Design Projects page.

#### Linux/Unix
Once you have confirmation that your website has been set up and your groups web files have been created, you are ready to publish your site to the CEIAS web server. Access to the web server is available via a SMB Client: smb://arshares.ucc.nau.edu/web/ceias.nau.edu/capstone/projects/

#### Mac
Once you have confirmation that your website has been set up and your group's web files have been created, you are ready to publish your site to the CEIAS web server. Access to the web server is available via a SMB connection using the "Connect to server" tool in Mac Finder.
On Mac's Finder's toolbar find the "Connect to server" dialog and connect to: smb://arshares.ucc.nau.edu/web/ceias.nau.edu/capstone/projects/ and then navigate down under <DEPARTMENT>/<YEAR>/<GROUP-NAME>
e.g.: smb://arshares.ucc.nau.edu/web/ceias.nau.edu/capstone/projects/ME/2008/Prometheus
After uploading your web documents you can view your page from a web browser at
http://ceias.nau.edu/capstone/projects/<DISCIPLINE>/<YEAR>/<GROUP-NAME>
Or find your project on the D4P Senior Capstone Design Projects page.
