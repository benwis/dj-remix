# DJ Remix

This is a remake of Fly's LiveBeats app in Remix, so Ryan can do some performance stuff(probably) and as a portfolio project. The goal, as @mrkurt put it is:

> "... build a multi user music player" is really the only requirement, github auth is interesting if you want to show that for remix, but I think the most interesting story is a dynamic app that goes all the way down to grabbing an mp3 from somewhere and playing it in sync across devices"

Built using Remix, Fly's Postgres service, and hosted on a Fly VM. I was going to use Prisma, but since Prisma 2 doesn't support subscriptions, I may go with Hasura instead.

Details of Fly's LiveBeats version can be found [here.](https://fly.io/blog/livebeats/)