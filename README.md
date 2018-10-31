# Extreme Carpaccio
Extreme Carpaccio is a coding game designed to encourage and favour incremental development and Continuous Delivery best practices.

During a Extreme Carpaccio session, the facilitator uses his/her computer as a server and sends HTTP requests to participant machines (generally organised in teams). Each request is a purchasing order, like those you have when you buy something somewhere. Participants then calculate the order's total amount and send the correct response back to the server. For every correct response, the participant earns points and increases his/her score. For bad responses, penalties are charged and the participant loses points. Participants should slice (or decouple) the problem in order to deploy small chunks of the solution into production as soon as possible and then score before others. This is the purpose of this exercise: define a slicing strategy, implement, deploy, check feedback, adapt the strategy, implement, deploy... and iterate as fast as possible. **Those who don't slice and try go to production only once the whole solution is implemented risk to spend too much time before scoring, leaving the way free to other teams win.**

This workshop, kata, or coding game is intented to help teams to practice concepts like Continuous Delivery, Lean Startup, eXtreme Programming, Agile Development, and more.

Ready for the challenge? 

If you are a **participant**, go to [clients/](https://github.com/dlresende/extreme-carpaccio/tree/master/clients) to get more instructions and start playing.

If you are a **facilitator**, go to [server/](https://github.com/dlresende/extreme-carpaccio/tree/master/server) and find out how to facilitate a session.

Have fun :D

## People running Extreme Carpaccio
- Find out what people are saying about Extreme Carpaccio on [Twitter](https://twitter.com/search?vertical=default&q=%22extreme%20carpaccio%22%20OR%20%22Xtreme%20carpaccio%22%20OR%20%23ExtremeCarpaccio&src=typd)


## Start and test the setup for dummies (with a node client)
1. cd into server
2. npm install
3. npm start

---------------------------------------

1. cd into clients\javascript\node-plain
2. npm install
3. npm start
4. note the ip and port
5. go to localhost:3000 in your browser (= server dashboard)
6. register you user via the ip and port shown in step 4
7. check console output