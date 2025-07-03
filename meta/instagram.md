# Instagram

## Deactivate your account but keep your data

1. Follow official guide to download your data https://www.facebook.com/help/instagram/181231772500920#downloading-a-copy-of-your-information-on-instagram.
2. Clean your data to keep only what's important to you.
  > [!NOTE]
  > In my case I had to unzip the downloaded archive, delete unwanted files () and save them to my storage:
  ```bash
  # find and remove binary files wildcarded with `._*`, related to their `.json` correspondants, but that are no value to me
  find . -name '._*' -delete
  ```
3. Check the data still available on the platform, visibility & privacy settings and adjust them accordingly. Think of how you want your account to remain online in between the deletion request and the actual deletion. During these periods, the service can impose policies that you don't necessarily agree with, but it's too late to log in again as your request is pending.
4. Request account deletion.

## Ambition

Now that we have our data. It would be nice to visualize seamlessly, ehm?
Apps ideas:
 - messaging app to navigate the conversations from our data archive.
 - bookmark app to navigate posts, saved items & places
