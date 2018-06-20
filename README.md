# googlecloud-howto

### Install Google Cloud SDK on a Mac
```sh
$ curl https://sdk.cloud.google.com | bash
```
or 

```sh
curl https://dl.google.com/dl/cloudsdk/release/install_google_cloud_sdk.bash | bash
```

### restart the terminal
```sh
$ source ~/.bash_profile
```
### Add this to your bash_profile file
```sh
 export PATH="$HOME/google-cloud-sdk/bin:$PATH"
```
### verify that the path exist in your bash_profile
