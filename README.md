# Relax Data Science Challenge

## Contents:
 
1. A user table [`takehome_users.csv`](./takehome_users.csv), with data on 12,000 users who signed up for the product in the last two years. This table includes:
- name: the user's name
- object_id: the user's id
- email: email address
- creation_source: how their account was created. This takes on one of 5 values:
  - PERSONAL_PROJECTS: invited to join another user's personal workspace
  - GUEST_INVITE: invited to an organization as a guest (limited permissions)
  - ORG_INVITE: invited to and organization (as a full member)
  - SIGNUP: signed up via the website
  - SIGNUP_GOOGLE_AUTH: signed up using Google Authentication (using a Google email account for their login id)
- creation_time: when they created their account
- last_session_creation_time: unix timestamp of last login
- opted_in_to_mailing_list: whether they have opted into receiving marketing emails
- enabled_for_marketing_drip: whether they are on the regular marketing email drip
- org_id: the organization (group of users) they belong to
invited_by_user_id: which user invited them to join (if applicable).


2. A usage summary table, [`takehome_user_engagement.csv`](./takehome_user_engagement.csv), that has a row for each day that a user logged into the product.
Defining an adopted user as a user who has logged into the product on three separate days in at least one seven day period, identify which factors predict future user adoption.

3. We suggest spending 1-2 hours on this, but you're welcome to spend more or less. Please send us a brief writeup of your findings (the more concise, the better no more than one page), along with any summary tables, graphs, code, or queries that can help us understand your approach. Please note any factors you considered or investigation you did, even if they did not pan out. Feel free to identify any further research or data you think would be valuable. Analysis in [`relax_data_science_challenge`](./relax_data_science_challenge.ipynb)


## Getting Started

### Prerequisites

- [Download Anaconda](https://www.anaconda.com/distribution/).
- Run Anaconda Navigator and launch a jupyter notebook and open the files listed below.

Packages applied in this project (numpy, scipy, matplotlib, pandas, seaborn, sklearn, datetime) do not require installation (default packages in anaconda). They only need to be imported in the notebook. 