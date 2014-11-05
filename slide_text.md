# In the Beginning
## From Back to Front
* Determined we wanted to move towards a responsive SPA
* Transition our existing apps from Tomcat to Ember
*  Reduce dependecy on monolithic Java/Spring components
*  Decrease time to deploy
*  Increase client-script specialization
*  Framework discovery and vetting
   * Bootstrap
   * Ember


## Rocky Road
* Started with Ember 0.8
* Ember Data all the way
* Custom auth required server persistent session
* Initially built custom adapter to use websockets
* Custom CMS solution
* Lots of caching issues
* Trying to grow with changes to Ember

## Our Stack
* Apache
* Tomcat
* Node.js => Java API
* Ember.js
* Require.js

Moving to Ember-Cli now

## Requirements
* ad support
* lottery
* feature flags
* cms support (flexpub)


# Learning from our Mistakes

## Hard Links - Hard Truths
### Disadvantages:
* Lots of hard links in your app
* User has to reload the app each time they click away

### Advantages:
* One app, segmented by route
* Can use {{link-to}} inside app

## Classphotos
* nested routing
* started using components
* started taking advantage of router hooks

## Other Stuff
* Require.js
* Code organization
* Refactoring 

# Onward and Upward

## Ember-CLI
* initializers!
* store.filter
* 

## Managing Data
* pulling in our currentUser from Tomcat and injecting into the store
* 