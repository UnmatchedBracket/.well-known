you wanna use github.io as a bksy handle too?
## i gotchu
1. make a repo named `.well-known`
2. on the repo go to **Settings** -> **Pages** and under "**Build and deployment**" set **Branch** to `main` and **Save**
3. back in bluesky go to **Settings** -> **Account** -> **Handle** -> **I have my own domain**
4. select **No DNS Panel** and copy the text starting with `did:plc:`
5. back in that repo make a file named `atproto-did` and put in that text
6. commit and wait for github pages to deploy (verify that it worked by going to `https://<yourname>.github.io/.well-known/atproto-did`)
7. back in bsky click "**Verify Text File**", and if it works then click "**Update to \<yourname>.github.io**" 
