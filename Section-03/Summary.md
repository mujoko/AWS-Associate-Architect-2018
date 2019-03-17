we learn that identity access management consists of the following consists of users groups roles and

policies.

Users are our end users.

They belong in two different groups which we can create so we can have developer groups human resources

marketing etc. roles we create for other AWOS services.

So if we want our little virtual machine in the cloud to be able to access S-3 in order to do that it's

going to need a row.

And in this section of the course we created S-3 admin access role.

We haven't used that yet but you'll see how we can use that in the easy to section of the course.

And then we learnt that basically all of our uses groups and rolls the way they get permissions is through

policies policies is made up of Jason or javascript object notation which looks just like this.

And this policy that you can see here on your screen is god mode.

And essentially it's saying effect allow action or wild cards so allow the action of everything on the

resource of everything so resource wild card.

So that is a god mode policy and don't worry it's beyond the scope of this exam.

Being able to you know go in and create your own policies or be able to write them from scratch when

you go on to do the certified security specialty you're going to get a whole bunch of different policies

thrown at you some which conflict with each other and you have to figure out what a user can and cannot

do based on those policies.

That's actually really entertaining to do because it's kind of like doing a really complicated Sudoku

puzzle or a crossword but once you come to the right answer there is only one right answer and it feels

really good.

Solving that.

So if you didn't get the chance I would recommend going on and doing the certified security specialty.

It is one of the most valuable certifications to have in I.T. right now because after all who doesn't

want to be certified in security on the cloud.

So what else have we learned so far.

Well we learned that I am is universal.

When you create a user that user can log in anywhere in the world it's not like they look down to just

being able to log in to Sydney or to London for example that the root account is simply the account

that's created when you first set up your AWOS account and it has complete admin access.

We also learned that new users have no permissions when they're first created.

So you're going to have to assign permissions using policies and that new users are assigned an Access

KEYT and secret access key.

When first created it is optional.

So you can have two different types of access you can have console access or programmatic access.

But when you get an access key idea and secret access key you're only ever going to see the once.

And you cannot use these to log in to the console so you cannot use your access key idea and secret

access data log into the console is used for programmatic access.

We're going to see what we mean by programmatic access in the easy to section of the course.

We also learned that you can only view all of these things whether it's the password the access key

idea or secret access key.

Only once if you lose them you can go ahead and regenerate them.

So just bear that in mind when you do get that CSI out do save it in a secure location.

We also learned that we should always set up multi-factor authentication on our account.

That means if someone takes a username and password they still can't log in without having our access

to our smartphone or without having access to our hardware MFA.

You might want to use RSA tokens for example and then we finally learned that you can create and customize

your own password rotation policies so we can add you know uppercase letters lower case letters going

to be a minimum of 12 characters you need a special alphanumeric character in there et cetera et cetera.

So that is it for I am.

It's very very basic stuff.

A little bit.

Try don't worry about it.

We're going to have a lot more fun as we move on in the next section we're going to cover.

S-3 S3 is a way of storing objects or files in the cloud.

And then after we've learned all about S-3 we're going to move on to easy too which is our machines

in the cloud.

We're going to start talking about how to use H2 and like serve you know application and database server

architectures.

And at the end of the easy to a section of the course we're going to go completely Servilius we're going

to look at the new way of cloud computing which is to try and not use virtual machines at all but instead

use a whole bunch of AWOS micro services and you're even going to write your own.

Are you going to create your own Alexis skills in that section of the course so you can have an awful

lot of fun as we move forward.

So that is it for this section.

Go ahead and review everything that you've learned.

If you have any questions please let me know.

And if not feel free to move on to the next section.

Thank you.


Autoscroll active
Questions
Search for a question
Search for a question
15 questions in this lecture
SK
Alarm per User
Can we create an alarm for a particular user which we created?
mahesh pcu
Basic plan
When I click cloudwatch under services It says below.Your service sign-up is almost complete!Thanks for signing up with Amazon Web Services. Your services may take up to 24 hours to fully activate. If you’re unable to access AWS services after that time, here are a few things you can do to expedite the process:Make sure you provided all necessary information during signup. Complete your AWS registration.Check your email to see if you have received any requests for additional information. If you have, please respond to those emails with the information requested.Verify your credit card information is correct. Also, check your credit card activity to see if there’s a $1 authorization (this is not a charge). You may need to contact your card issuer to approve the authorization.If the problem persists, please contact Support:
SR
ROOT User signing out !!!
using IAM I have created a user account. when I tried to login with my user account using the url, my root user account got signed out. Root account and user account cannot be logged in at the same time?
SB
Billing alert
Few members have posted questions on billing alert, this session was recorded on old UI. There are few changes and need some updates. Can someone please help us understand the steps to create billing alert in the updated UI?
G
Not able to access Cloudwatch service
I am facing below issue while trying to go into CloudWatch for lab activities.Please help."Your service sign-up is almost complete!Thanks for signing up with AISPL. Your services may take up to 24 hours to fully activate. If you’re unable to access AWS services after that time, here are a few things you can do to expedite the process:Make sure you provided all necessary information during signup. Complete your AWS registration.Check your email to see if you have received any requests for additional information. If you have, please respond to those emails with the information requested.Verify your credit card information is correct.If the problem persists, please contact Support:"My card details are all correct and the money is debited during the verification
RK
Unable to download Vedio in offline mode
Hello:I am not able to continue course whenever net is not available, can you please tell how to download video for offline mode?
AD
I think what course explained is old. New UI is seems different. IS there someone who can help me for setting alarm.
W
Billing alert
Hello.I am unable to follow the billing alert set up. My UI seems very different and I am having a hard time adding email list after setting up the billing alert. On the new UI there is a select metric selection as well could you please help me understand how that works.thanks.
O
Billing Alert
Syed Asif
Create Alarm
Firstly we need to save preferences for email notification under the username - Preferences to  create a Alarm for billing notification
SO
how user can login via console or CLI ?
S
Read only access to all AWS services
How can we grant  access to AWS console with read access to all the services on AWS. users should not have write access to any services in any region. How can we  achieve this using IAM? Do we have to write a custom policy or do we have a default role /policy available?
SR
Can we make a region permanent for our AWS account ?
Hello,When I create my AWS account, It has selected nearby Region. Then After 1 day when I re login it has changed to some other region. If I create all my content/data etc in one region.  Can I access from other regions ? How to make a region permanent on my account ?Can you please explain how this works ?
DA
How to connect aws through command line?
AS
what is roles..
problem in understanding roles