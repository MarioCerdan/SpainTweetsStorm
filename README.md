storm-twitter-Spain-word-count
========================

Sample project based on https://github.com/abh1nav/dvto1 demonstrating real-time computation Storm framework (https://github.com/nathanmarz/storm).
The code subscribes to Twitter's Sample feed, keeps stats on words occuring in Spain-country tweets and logs top list with of words with most count in every 10 seconds.

This project contains a simple storm topology that connects to the sample stream of the Twitter Streaming API and keeps stats on words occuring in tweets and prints top list of words with highest count in every 10 seconds.

To get started:
* Clone this repo
* Import as existing Maven project in Netbeans
* Run Topology.java

You'll need to have valid Twitter OAuth credentials to get the sample working.
For the exact steps on how to do that, visit https://dev.twitter.com/discussions/631.


Done for educational purposes, based on https://github.com/davidkiss/storm-twitter-word-count
