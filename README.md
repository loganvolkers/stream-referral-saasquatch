# stream-referral-saasquatch

A data stream generator for the Referral SaaSquatch API, written in python 3.

## Install

Clone this repository, and then:

```bash
› pip install -r requirements.txt
```

## Run

#### Run the application

`stream-referral-saasquatch` can be run with:

```bash

WOOTRIC_CLIENT_ID=<clientid> WOOTRIC_CLIENT_SECRET=<clientsecret> python stream_wootric.py [FILENAME]

```

Where `clientid` and `clientsecret` are the 64-character strings retrieved from the API section of your Wootric account settings page.
