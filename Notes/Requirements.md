# Requirements

User should be able to...

1. Work out how much they spent on a holiday 
2. To be able to assign combinations of custom tags 
3. Give user a list of transactions they need to update!
4. be accessed on a phone
5. have an independent data storge to store this stuff
6. Provide ability to ignore if necessary 

# User Stores
As a user...I want to check how much I spent on my holiday to Portugal
and how long the holiday was 
As a user...I want a simply checklist of items I need to update for 
As a user...I want to know howm much I spent on Lime bikes the last months 
to date 
As a user...I want to know how much total assets have changed over time 
As a user...I want to account for how much cash I have as well
As a user...I want to account for non-monzo e.g. cash transactions
As a user...I want to record mistakes e.g. not using Clubcard
As a user...I want to automatically associate merchants with items
As a user...I want to hide certain categories
As a user...I want to specify what type of 'Day' it was e.g. NOMAD day? How much I spend vs WFH on average


# Ideas
Use webhooks to pull transaction when it occurs? But susceptible to 
being missed if API is down 


# Non-functional Requirements
1. C# backend 
2. NodeJS Backend (api to an api)
3. Unit testing!
4. Front-end is React-based SPA (for now, then upgrade to Next.JS)



# Objects

User 
    UserID
    EmailAddress
    BearerToken
    Tags
    UserLocation = England (if not england...then add SA tag for instance)


Transaction
    ID
    Name
    DateTime
    Tags 
    BalanceBeforeTime
    BalanceAfterTime


# Sprint 1 
1. Basically just consume the Monzo API
2. List accounts, balance, and transactions 
nicely 
3. User inputs bearer token into field 
4. Get a cheap looking UX shell with "Tabs" for accounts, transactions etc
5. Just a playground basically
6. 2 weeks estimate

