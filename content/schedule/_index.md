---
title: Schedule of Shows
layout: schedule
socialShare: false

---

## Schedule

![schedule August 2024 week 4](/schedule/2024Schedule-Aug-week4-finalised-RayOfSwords.png)

## Shows
### Genderful Podcast

Every other Monday at <span id=genderful_podcast_time> </span>

biweekly talk show interviews gender-diverse people about their special interests.

### Shenanigans

on 1st, 3rd, and 5th Tuesday at <span id=shenanigans_time> </span>

co-op games with friends, often co-hosted by MeowsterThemself and Sunberry.

### Doing the Work

2nd Tuesdays of the month at <span id=doing_the_work_time> </span>

intersectional social justice self-education stream

### In The Meme Time

1st Thursday of the month at <span id=in_the_meme_time_time> </span>

reacting to memes from Meowster's Clowder Discord server's starboard

### Contributor Appreciation Day

2nd Thursday of the month at <span id=contributor_appreciation_day> </span>

collaborative stream with assorted Clowder Contributors to honor their effort - this stream is sometimes also a mini-mutual aid event for community members.

### Tarot 4 Trans (T4T)

3rd Thursday of the month at <span id=tarot_4_trans> </span>

Momster (Meowster’s mom) joins MeowsterThemself to read tarot for the community, often working with [The Next World Tarot](https://www.silversprocket.net/next-world-tarot/) by Cristy C. Road.

### Clowder Takeover

4th week of the month

Meowster's friends takeover the channel for a week, providing guest content while MeowsterThemself is doing self-care, admin, or on vacation.

### Special Events

#### Mutual Aid Streams

Often in collaboration with Gender Federation or Disabled Content Creators Collective.

#### Memorials

Trans Day of Remembrance (November 20th each year)

Disability Day of Mourning (March 1st each year)

#### Streamiversaries

The GenderMeowster Twitch channel celebrates its affiliate anniversary each year around August 3rd.

Check out our [Streamloots integration](https://www.streamloots.com/gendermeowster) for some of our gaming streams!

For the most up-to-date information about our schedule, including cancellations or last minute changes, please check our socials and discord server for more info.


<script src="/luxon.min.js"></script>
<script>

// Genderful Podcast
var genderful_podcast_time = luxon.DateTime.fromISO("2017-05-15T15:30:00", { zone: "America/Los_Angeles" });
var genderful_podcast_time = genderful_podcast_time.toLocal();
var genderful_podcast_time = genderful_podcast_time.toLocaleString(luxon.DateTime.TIME_SIMPLE)
console.log("genderful_podcast_time");
console.log(genderful_podcast_time);
document.getElementById("genderful_podcast_time").innerHTML = genderful_podcast_time;

// Shenanigans
var shenanigans_time = luxon.DateTime.fromISO("2017-05-15T11:00:00", { zone: "America/Los_Angeles" });
var shenanigans_time = shenanigans_time.toLocal();
var shenanigans_time = shenanigans_time.toLocaleString(luxon.DateTime.TIME_SIMPLE)
console.log("shenanigans_time");
console.log(shenanigans_time);
document.getElementById("shenanigans_time").innerHTML = shenanigans_time;


// Doing the Work
var doing_the_work_time = luxon.DateTime.fromISO("2017-05-15T11:00:00", { zone: "America/Los_Angeles" });
var doing_the_work_time = doing_the_work_time.toLocal();
var doing_the_work_time = doing_the_work_time.toLocaleString(luxon.DateTime.TIME_SIMPLE)
console.log("doing_the_work_time");
console.log(doing_the_work_time);
document.getElementById("doing_the_work_time").innerHTML = doing_the_work_time;



// In The Meme Time
var in_the_meme_time_time = luxon.DateTime.fromISO("2017-05-15T11:00:00", { zone: "America/Los_Angeles" });
var in_the_meme_time_time = in_the_meme_time_time.toLocal();
var in_the_meme_time_time = in_the_meme_time_time.toLocaleString(luxon.DateTime.TIME_SIMPLE)
console.log("in_the_meme_time_time");
console.log(in_the_meme_time_time);
document.getElementById("in_the_meme_time_time").innerHTML = in_the_meme_time_time;


// Contributor Appreciation Day
var contributor_appreciation_day = luxon.DateTime.fromISO("2017-05-15T11:00:00", { zone: "America/Los_Angeles" });
var contributor_appreciation_day = contributor_appreciation_day.toLocal();
var contributor_appreciation_day = contributor_appreciation_day.toLocaleString(luxon.DateTime.TIME_SIMPLE)
console.log("contributor_appreciation_day");
console.log(contributor_appreciation_day);
document.getElementById("contributor_appreciation_day").innerHTML = contributor_appreciation_day;


// Tarot 4 Trans (T4T)
var tarot_4_trans = luxon.DateTime.fromISO("2017-05-15T11:00:00", { zone: "America/Los_Angeles" });
var tarot_4_trans = tarot_4_trans.toLocal();
var tarot_4_trans = tarot_4_trans.toLocaleString(luxon.DateTime.TIME_SIMPLE)
console.log("tarot_4_trans");
console.log(tarot_4_trans);
document.getElementById("tarot_4_trans").innerHTML = tarot_4_trans;


</script>
</body>