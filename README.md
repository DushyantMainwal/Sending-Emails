# Sending-Emails
Sending Emails (with &amp; w/o GMail API)

Requirements:
1) 3 Jar Files (activation.jar, additionnal.jar, mail.jar)
2) Gmail API Integration

# How to implement:
Copy Jar file in libs folder and include them using:
```groovy
dependencies {
    implementation fileTree(dir: 'libs', include: ['*.jar'])
}
```

# With OAuth2:
1) Go to https://console.developers.google.com/apis/
2) Serach Gmail API
3) Add your credentials

# For More Info:
Go to: https://developers.google.com/gmail/api/guides/sending 
