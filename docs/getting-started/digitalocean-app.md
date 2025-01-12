# DigitalOcean 1-Click App #
You can deploy PhotoPrism with a few clicks on DigitalOcean.

## Register an account at DigitalOcean ##
- [Register at DigitalOcean](https://m.do.co/c/ca260247b5c2)

!!! info
    When using the referral link above, new users MAY get $100 in credit over 60 days.

## Install PhotoPrism ##
- Sign in to DigitalOcean
- Open the [PhotoPrism listing](https://marketplace.digitalocean.com/apps/photoprism) in the marketplace
- Click *Create PhotoPrism Droplet*

![Screenshot](img/create-photoprism-droplet.png)

### Configure your droplet ###
#### Choose an image ####
The PhotoPrism image will be pre-selected

![Screenshot](img/1-do-setup.png)

#### Choose a plan ####
We recommend hosting PhotoPrism on a server with at least 2 cores and 4 GB of memory. 
Indexing and searching may be slow on smaller Droplets, depending on how many and what types of files you upload.

![Screenshot](img/2-do-setup.png)

#### Choose a datacenter region ####

![Screenshot](img/3-do-setup.png)

![Screenshot](img/4-do-setup.png)

#### Choose your authentication mode ####

![Screenshot](img/5-do-setup.png)

#### Finalize your droplet ####
Finalize your droplet and click *Create Droplet*
![Screenshot](img/6-do-setup-edited.png)

![Screenshot](img/7-do-setup.png)

Your droplet is now being created.

## Find your initial password ##
- Click *More*

![Screenshot](img/do-more-options-edited.png)

- Click *Access console*

![Screenshot](img/do-access-console-edited.png)

- Launch the console as root

![Screenshot](img/do-launch-droplet-console.png)

- Within the console type ```cat /root/.initial-password.txt``` and click enter
- Copy your initial password

## Open PhotoPrism ##
- Click *Get started*

![Screenshot](img/do-get-started-edited.png)

- Click *Quick access*

![Screenshot](img/do-quick-access.png)

!!!info
    In case you have no domain and let's encrypt set up you will see the notice "Your connection is not private". 
    Click *Advanced* and click *Open page*.

- Use username "admin" and your initial password to sign in
- You may [change your password](../user-guide/settings/account.md) using the Web UI

## Add files ##
- Decide whether you want to [index or import your files](../user-guide/library/import-vs-index.md)
- [Add files to your import or originals directory using Webdav](../user-guide/library/webdav.md) or use the [Web UI](../user-guide/library/upload.md) to upload files to your import directory
- You might also setup [automatic sync](../user-guide/sync/sync-phone.md) from your phone

