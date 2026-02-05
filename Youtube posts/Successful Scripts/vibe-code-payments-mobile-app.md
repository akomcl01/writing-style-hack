---
Title: Build a Mobile App with AI That Accepts Payments (Complete Guide)
Channel: Riley Brown & Muhammad
Type: Tutorial / Walkthrough
Format: Two hosts, screen recording with phone demo
---

# BUILD A MOBILE APP WITH AI THAT ACCEPTS PAYMENTS

## INTRO

**RILEY:**
Today, we're going to build an app with AI that can actually accept payments. This was never possible until today. This is going to be a complete vibe coding a mobile app guide that you can send to the app store and collect payments — which means make money.

We're first going to build a mobile app with AI. Then, we're going to create a paywall that actually works without writing a single line of code. Then, we're going to send our app to the app store. And then we're going to test the paywall and see if it works and allows us to actually accept payment.

My name is Riley Brown and this right here is Muhammad. And we make videos like this every single week. So make sure to subscribe and hit that like button. It helps us out a lot.

Let's dive in.

---

## THE $5M APP WE'RE CLONING

**RILEY:**
So Muhammad, what app are we building today?

**MUHAMMAD:**
We're going to make a construction estimator app.

**RILEY:**
So there's no way this app makes money.

**MUHAMMAD:**
Dude, this app makes $4.8 million and it's growing. I've been tracking it for the last 2 months. It's exploding right now.

Basically what they do is they help different construction companies make estimates about projects with AI. You can see some of these pictures here — it'll give you AI generated images for like a bathroom remodel or estimations in seconds that's probably just generated with AI.

This app is exploding. And I think that we can make this in Vibe Code.

**RILEY:**
Okay.

**MUHAMMAD:**
So we'll make it in Vibe Code and then we will actually add a paywall so that we can charge users.

I have a prompt ready here. It's basically just explaining to the agent to make the base of it — not the functionality because we'll add that later since it's pretty heavy on AI.

I just told it what it does:

*"I want to build the base of my app which will give contractors an estimate on the price of a job. It will be for various types of contractors such as home improvement, fences, remodeling, kitchen upgrade, bathroom upgrade, etc. It will be used to keep track of progress of current jobs and to estimate new jobs. We will use AI for this, but do not implement this now. For now, build a beautiful base. We will add the functionality later."*

**RILEY:**
I like it. Cool.

---

## FIRST PROMPT WITH CLAUDE OPUS

**MUHAMMAD:**
All right. So we're just going to copy that and then head over to vibecode.dev and paste that in. I think I'm going to use Opus for this.

**RILEY:**
Got to use Opus, especially for the first prompt.

**MUHAMMAD:**
Yeah, we can just send that. So Vibe Code uses Claude Code out of the box. It's literally Claude Code that builds mobile apps and you don't need to do any setup or anything. It's going to build the app and then we'll make adjustments.

I guess while it's loading, we could probably ready up the API.

**RILEY:**
Yeah.

---

## ADDING GEMINI & OTHER FEATURES

**MUHAMMAD:**
So I can go over to the API tab. We have a few new ones that I added today. You can click this arrow to read more and see the pricing.

I think I'm going to use Nano Banana for the image generation. So maybe I want to keep it in the Gemini family and just use Gemini 3.

**RILEY:**
I think Gemini 3 is really good at images as input.

**MUHAMMAD:**
Yeah. And it's pretty cheap. So we can add to prompt: "Please use Gemini 3 for the AI estimation."

So it's done loading. And now what? I scan the QR code.

**[Muhammad scans QR code with phone, app appears on screen via Bezel]**

**MUHAMMAD:**
So you just scan the QR code once it's done loading. And this is the app that it's created.

It's okay. Too many colors for my life.

**RILEY:**
You don't like it?

**MUHAMMAD:**
The purple annoys me, but it's fine. It looks like it has all the features. You want to go through it?

So this is my homepage. We got quick estimates here. That's the same as this new estimate tab. We have jobs to see our current jobs — estimate scheduled, in progress, completed. We have this profile page which I guess we can change to the business profile. Edit profile, notifications.

These all don't do anything because I did tell the agent not to do anything.

**RILEY:**
Why don't we just add that AI?

**MUHAMMAD:**
Yeah. So we're adding Gemini 3 Pro. I think it's the best for image input. "Please use Gemini for the AI estimates."

So I can take a photo and it gives estimates. "Take a photo and it gives structured estimates."

It seems to be the only AI feature. We can add that Nano Banana one later where you take a picture of a bathroom and it remodels it, but we can do that later. We can just do this for now.

And I think we could pair it with the image that we generated. And please use this image as the app icon throughout the app.

---

## TESTING THE AI ESTIMATE

**MUHAMMAD:**
All right. Looks like it's done. So we asked it to use Gemini for actually giving the estimates.

I see it. The button looks different. "Fill in category, title, and description to use AI estimate."

**RILEY:**
I know you spent a lot of time working on this studio, but I think it needs an upgrade.

**MUHAMMAD:**
Okay. I think it needs a painting upgrade. And I think we need to paint the walls rainbow.

**RILEY:**
Rainbow?

**MUHAMMAD:**
Yeah. And the walls are black now, but I want rainbow. So I'm assuming the AI will estimate the price. So then we can take a photo here.

**[Takes photo of wall]**

$6,000. Medium confidence on that.

**RILEY:**
Medium confidence. $6,000.

**MUHAMMAD:**
Gives you a scope of work: "Apply a vibrant rainbow color scheme to the painted walls." 5-7 days. And it gives you a cost breakdown of the labor and material.

That's cool. We could probably ask it to be more specific on the cost breakdown if you wanted to.

**RILEY:**
Yeah, I mean I think we could do that in version two. I think we should just get the MVP up. Should we add the paywall or should we do the Nano Banana next?

**MUHAMMAD:**
Let's get Nano Banana — that would be like one prompt. Then we'll do the paywall and start accepting payments.

---

## TESTING NANO BANANA PRO IN APP

**MUHAMMAD:**
So I can go over to the API tab and then go to images — Nano Banana Pro, the new one.

"I also want after the estimate to generate an image with the changes applied."

**RILEY:**
So wait, that'll happen automatically? Like when it showed you the $6,000, it'll just show the rainbow wall instead?

**MUHAMMAD:**
Yeah. And I want to add one thing — while it's loading and now we're going to have multiple AIs loading at the same time, I want the original image being shown there so the user can see it while it's loading. And then once it's done loading, it'll switch to the new image and also have the cost breakdown below it with all of the other stuff. And also let the user go full screen into the new photo so they can see it all and exit.

**RILEY:**
That sounds like a good prompt. Ship it.

**[Agent builds]**

**MUHAMMAD:**
It's done. Let's give it a test. Let's see the Nano Banana. We can do painting again — do the rainbow.

**RILEY:**
I like the rainbow.

**MUHAMMAD:**
Rainbow walls. "I want to paint these walls rainbow." Take a photo.

Nice. Okay, there we go. Last time it was literally just the spinner over a black screen, which is boring. This is looking a lot better.

Whoa. Okay, so there's a cool little animation and I can see the rainbow walls. Very cool. I could show those to my clients and be like, "This is what it would look like."

Last time it said $6,500.

**RILEY:**
You could definitely fine-tune it, but it works. I think this is a good version one. After all, it is an estimate.

**MUHAMMAD:**
And so we can use that estimate and it pops up there. And then you can continue doing these upgrades to this app. We can do so many things — we can make all of this work, set up database if we wanted to. But the point of this video is to show off the payments.

---

## ADDING PAYMENTS TO OUR APP — STARTING THE FLOW

**RILEY:**
So what we wanted to really do in this video is to focus on how to make money because I feel like this app is already good enough for someone out there to buy the app after just three prompts.

**MUHAMMAD:**
So we're going to add payments and we're not going to write a single line of code. I want to talk about what it means to add payments and what happens when we add payments.

It's a new feature now that we have a payments tab at the bottom. I'm going to start the flow from the very beginning. This is how you will see it if you've never done this before.

When you press payments, it says "Connect RevenueCat."

---

## WHAT IS REVENUECAT?

**RILEY:**
So what is RevenueCat?

**MUHAMMAD:**
RevenueCat is basically the middleman that sits between you and your users. For anyone that's ever made a web app, it's kind of like Stripe, but not really.

With RevenueCat, you get the system payment. Like if you ever subscribe to something on Apple and there's a little card that comes up and you double click the home button and it scans your face and you pay for it — that is native to Apple and the purchases go to Apple and you can easily manage subscriptions.

Basically it just makes everything a lot easier.

---

## CONNECTING REVENUECAT

**MUHAMMAD:**
So the first step we're going to do here is connect RevenueCat and then it automatically creates a project.

To connect it, we just hit this button. I'm already signed in. It'll just ask you to sign in and then this will come up. And then you just authorize it — basically giving Vibe Code access to your RevenueCat.

You can create an account as well. It's free. We can authorize it and it was successful.

First, I have to enter my display name. This is the name that you're going to see on the home screen that users will see. I already have a name here — Contractor Pro. So I'll just use that.

During this process, it creates a RevenueCat project and then an Apple app for your RevenueCat. A RevenueCat project is sort of like this top-down group for your app. It has all of the data of what users have purchased, what subscriptions. And it's cross-platform.

When you create a new RevenueCat project, there's different products that you can have within it.

---

## PROMPTING THE PAYWALL WITH PRODUCTS

**MUHAMMAD:**
Once it's done loading, it says what to do next. We've put some placeholders in like "create a monthly subscription for $4.99, make the settings page premium only, create a lifetime access product," etc.

Usually that step takes a long time because there's products and offerings and entitlements, but you don't have to worry about any of that because the agent can do it itself.

We can start with this pre-selected one, but instead of $4.99, I kind of want it to be $9.99. So we're going to make it $9.99 for a monthly subscription. And a yearly plan for $49.99.

**RILEY:**
I like it.

**MUHAMMAD:**
And then what I like to do here is add a paywall when a user does a certain action in the app. I would say when the user tries creating a job.

So we can send that and see the agent pull. And so now it's loading.

Do you want to pull up RevenueCat? You can see the project that was created.

**RILEY:**
So if you go to RevenueCat, you can log into your account — obviously the same account that you connected. And here we can go — I have a bunch of projects. Contractor Pro.

That was our Contractor Pro. We have zero MRR obviously. We have no one who signed up so far.

**MUHAMMAD:**
But that will change when we start testing it because we're going to test it with sandbox data.

**RILEY:**
Right now you can either have real data or sandbox data. The sandbox data is basically what allows us to test it before you can turn it on.

**MUHAMMAD:**
So yeah, it's going to build the subscriptions inside of Vibe Code and then you can test it by doing a test purchase of the subscription and you'd see it inside of RevenueCat when your sandbox data is on.

And if we go to product catalog, it all starts out empty. Maybe the agent has added — no, it hasn't added anything yet, but it's doing that right now. The agent is currently adding a product.

---

## TESTING THE PAYWALL

**MUHAMMAD:**
Okay, it looks like it's done. We can test out the paywall by creating a new job.

Paint walls. Doesn't matter. We're just testing it out. Riley. Create estimate.

And that's my paywall. Wow.

**RILEY:**
Okay, so it added this paywall. How does it work? Can you use it?

**MUHAMMAD:**
Yeah. So let's hit the subscribe button. And then you're going to get this screen, which is just a test screen. This is not what your users are going to see — it's going to show the little thing that will scan your face if you want to do Apple.

We'll show that after we submit it to the app store. We can test a valid purchase of a monthly subscription and then it gives me the success message. So in theory it should show the $9.99 in RevenueCat.

**RILEY:**
So we can go back to RevenueCat, go to overview, and we can see I have one active subscription for $10 MRR. And at the bottom, it says a few seconds ago, someone signed up for $9.99.

**MUHAMMAD:**
Amazing. And then it created all the products and entitlements.

---

## ALTERING THE PAYWALL IN REVENUECAT

**MUHAMMAD:**
I do want to do one thing. RevenueCat has these new paywalls and this new paywall editor that you can use. Our paywall is okay, but it could be better. You can just select from an existing paywall.

They have a bunch of templates here. This one kind of matches us. We could obviously change all of this. I'm not going to change all of it right now. Just "Contractor Pro."

We can publish that. Confirm. Publish.

Then we go back to offerings and it looks like it's already linked to that paywall.

I can go back to the Vibe Code agent and ask it to please use the paywall I created in RevenueCat instead of ours since ours is a little ugly.

**RILEY:**
Just a little bit.

**MUHAMMAD:**
After you submit this to the app store, you can change the paywall live over the air. So it'll change instantly even after you deploy it in case we want to make any changes to it.

If we go back to product catalog, we will see that the Apple status is not ready yet. That's because we have to configure a few things inside of RevenueCat to make it work. It's only like three steps.

After this is done, we'll submit it to the app store.

**RILEY:**
Amazing.

**MUHAMMAD:**
Okay, it looks like it's done updating. So we should see the new paywall that we created in RevenueCat.

And there it is with our annual and monthly subscription. Sign up for annual this time.

**RILEY:**
Sure, why not.

**MUHAMMAD:**
Cool. We get the success message and then I should be able to create the estimate, which I just did.

And if we go over to RevenueCat and refresh, we will see $50 now.

**RILEY:**
Oh yeah.

**MUHAMMAD:**
And while it was loading, you canceled the previous user.

**RILEY:**
Do you want to show how you did that? Because sometimes you want to test the paywall again. But if you've already signed up in the app that you make, then you won't be shown the paywall again.

**MUHAMMAD:**
Yeah. And if you don't want to wait the 30 minutes, you can just click on the user like I just did and then scroll down and you'll see "delete user." And then we can confirm and then if you refresh the app inside of Vibe Code, then you'd be able to see the paywall again.

That'd be great if you wanted to test how it would work if a user canceled the subscription or something like that.

Cool. That's pretty much all set up.

---

## SHIPPING THE APP TO THE APP STORE

**MUHAMMAD:**
When you do set up payments inside of Vibe Code, we set it up such that when you submit to the app store, it'll just work immediately. You don't have to do anything.

The app is ready to be shipped to the app store and accept payments.

We can go over here to "share" and "publish to app store." And then we can just click a few of these buttons. That's the name I want.

We can make a logo — calculator with price tag. We could upload our own if we had one, but this is fine for now.

**RILEY:**
I think this is great. It's super easy to upload it later.

**MUHAMMAD:**
That looks good. We'll use that.

If you don't have an Expo access token, you can just click this link and get one and then just paste it in here. It's completely free. All you need is an Expo token which will allow the app that's built on Vibe Code to be sent to the app store.

Press "start build." Need that token. This usually takes like five minutes-ish. And then you'll get a success with a link to view the build process.

All right. Looks like the build is finished. If we head over to Expo, you can see that the build has succeeded and then the submission has succeeded.

**RILEY:**
Amazing. So if we go now to App Store Connect.

**MUHAMMAD:**
For those who are brand new and maybe they've just used the Vibe Code app a few times and sent an app to the app store — this is where you manage your app. This is where you would have to submit it through if you weren't doing it through this method.

**RILEY:**
And you will have to do some stuff on App Store Connect to get it on the actual App Store, like uploading screenshots for your app, uploading a description, privacy policy, and terms of services.

**MUHAMMAD:**
Those are all needed. If you click on the app, you'll see you can upload the screenshots here, description, keywords. If you don't know what else you need to do, you can just go to "add review" and it'll tell you a bunch of stuff that you need to do.

I don't have any of these done. You don't have to do these for the TestFlight.

TestFlight is basically the last time you're going to test your app before you submit it. So it's like production — everything is production level. Besides purchases, those are still sandboxed. But everything else is how it will be in the app store.

Usually when I submit an app, I like to test it in TestFlight. You can see that Expo created the TestFlight build.

But like I mentioned before, if we go back to RevenueCat and go to the products, which is basically our subscriptions, you'll see that there's some things that we need to do first.

---

## ADDITIONAL SETUP IN APP STORE CONNECT

**MUHAMMAD:**
Inside of App Store Connect, go to the main distribution page and if you scroll down on the left side, you'll see a place for in-app purchases and subscriptions. We did subscriptions. If you did in-app purchases, you'll go there.

We're going to go inside and then we can see that there's no products or groups.

You can add that manually in RevenueCat or you could ask the agent inside of Vibe Code to push the apps from RevenueCat inside of App Store Connect. So you don't have to do any manual configuration there.

**RILEY:**
Okay, let's see this.

**MUHAMMAD:**
It's one of the preset things: "Deploy my RevenueCat product to App Store Connect."

You can type this prompt and it will just create those products within App Store Connect.

**RILEY:**
Okay. So you would normally do what you just did before you type this?

**MUHAMMAD:**
Yeah. And if you do anything out of order, the agent will tell you.

It basically gave the same instructions. And then we can say "okay I've given the credentials, try again."

**RILEY:**
Can you scroll up to your original prompt? I just want to see it again.

You said "deploy and create my RevenueCat products to the App Store Connect with your connections." And the reason it wasn't able to do that is you didn't basically give RevenueCat those keys from your App Store Connect which allows you to do it.

**MUHAMMAD:**
Yeah. So now that I've done that, it should be able to create the two products because we had monthly and yearly. And a few other things that you don't have to really worry about.

**RILEY:**
Very cool.

**MUHAMMAD:**
Okay, so it looks like the agent is done. It pushed the monthly and yearly. It did that really fast, like 20 seconds. Just two little things and both products are now live in App Store Connect.

Now if we go back to our apps and go back to Contractor Pro, down to subscriptions, you will see "Contractor Pro Premium" and then you'll have a monthly subscription and a yearly subscription.

Now that you've done that, a few more little things that you have to do.

**RILEY:**
Great.

**MUHAMMAD:**
And this is just Apple being Apple. But once you do them once, you don't have to ever do them again. It's just a one-time setup.

Inside of my subscriptions, I'm going to go into one — my monthly subscription. And then you'll see the status here says "missing metadata." That basically means I just have to set up a few things like the pricing and the name.

Availability — I'll just do all countries. Subscription pricing — it was $9.99 and it'll automatically convert it to the currencies. Pretty soon the agent will be able to do this pricing stuff for you, but for now we're going to have to do that.

Localization — just the name of it. "Premium Contractor Pro." Add that.

This image is optional. You also need a screenshot of the paywall so Apple reviewers can look at it. I went on my phone and just took a screenshot of the paywall. I'm just going to drag and drop it in.

Review notes optional. It's pretty self-explanatory.

Once you do that, you can go back and do the same thing if you have two subscriptions. I'll do that off camera.

After you do that, you also have to do a localization for the group of the subscriptions.

**RILEY:**
So what is the group?

**MUHAMMAD:**
So I have two subscriptions technically — monthly and yearly. But they offer the same privileges. The only difference is how often they get charged and by how much. So there's two subscriptions of the same product — the group is the premium access.

**RILEY:**
Okay, that makes sense.

**MUHAMMAD:**
And if you have two different subscriptions that offer two different things, the agent will know and create two separate groups that you have to name.

Since both of my subscriptions are on the same paywall, we're just going to send the same picture. "Yearly sub." This should work. Save that.

You can see up here the status is now from "missing metadata" to "ready to submit."

---

## TESTING THE TESTFLIGHT VERSION

**MUHAMMAD:**
Now we're ready to test it on TestFlight.

We can go to TestFlight. We can see that the build number is one. And since Expo already created this group, I should have a link in my email to accept this.

In this case, I didn't get the email immediately. You should get an email that looks like this. And if you don't, you can go into internal testing and just select yourself and then just reinvite. And then you should get this email.

We're going to open the app inside of TestFlight.

**RILEY:**
Okay. So this is the app that we created on Vibe Code that we sent to the app store. Now we're opening it in TestFlight, not in Vibe Code.

**MUHAMMAD:**
And so now this is a production level app now.

**RILEY:**
Opens up instantly. It's the same app that we had in Vibe Code. Everything looks the exact same.

**MUHAMMAD:**
And then we can see the paywall and see if that works. Just do random stuff. "Riley." Create estimate.

And then we do get the paywall. And if you go to "continue," you'll get this Apple popup. We can subscribe.

Here you would put in your testing, your beta testing information. And then you'd put in your login information there and then it should go through.

I did that off camera to hide my password, but you would get that and then you just do continue and then cool — you get premium just like you would.

**RILEY:**
Wait, you just paid?

**MUHAMMAD:**
It wasn't technically paying. No, I didn't pay real money since it's TestFlight.

**RILEY:**
We're still doing TestFlight. Okay, that makes sense.

**MUHAMMAD:**
Essentially, I would have to pay if it was deployed on the app store. It's the same thing.

And then we go over to RevenueCat and it'll show up in the sandbox data. It'll switch instantly right when it's live on the real app store. Then it'll actually charge real money. But right now it's still sandbox data.

**RILEY:**
Is there anything that you need to do to make sure that the real payments go through?

**MUHAMMAD:**
No, it's already ready right now.

---

## FINAL THOUGHTS

**RILEY:**
So we built an app that allows us to take a photo of something and then it will analyze it with AI, generate a new image with AI, and we added a paywall with payments integrated.

**MUHAMMAD:**
Without writing a single line of code.

**RILEY:**
That's great. Anyway, so that's the video.

**MUHAMMAD:**
I encourage you guys — let us know in the comments what we should build next. This video was meant to focus mostly on the payment side.

If we missed anything or you get stuck anywhere, please join the Discord. I'll put a link to our Discord below and you can ask as many questions as you want. Kihan will be in there all week helping people get through with payments.

If you run into any problems, just let us know in the Discord and we'll help you through it.

I know this might have seemed like a lot towards the end, but we're going to work to make this easier and easier. And we're just going to make a ton of tutorials going forward until everyone kind of understands it.

**RILEY:**
Yeah, there it is. Thank you guys.

**BOTH:**
Peace.