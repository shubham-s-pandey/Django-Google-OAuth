# Django-Google-OAuth


Create OAuth client ID

    You can create your OAuth Client ID by filling out these details;
    Authorized Javascript origins (http://127.0.0.1:8000)
    Authorized redirect URL (http://127.0.0.1:8000/accounts/google/login/callback/)
    
Under admin panel:
Add a site

On the SITES section, click “sites” and fill out the details and click “Save”:

    Domain name: 127.0.0.1:8000
    Display name: 127.0.0.1:8000

Add social applications

Back to admin homepage, under “SOCIAL ACCOUNTS” section, click “Social applications” to fill out these settings:

    Provider: Google
    Name: Google API
    Client id: (your OAuth details)
    Secret key: (your OAuth details)


Link:
https://console.developers.google.com/
