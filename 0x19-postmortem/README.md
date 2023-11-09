# Incident Summary:

* Outage Duration: The outage gave us a good two and a half hours of "quality time" from 1:00 PM to 3:30 PM (WAT).

* Impact: Our login service decided to take a nap, leading to a 20% user disruption. Users were left knocking at the door, asking, "Who's there?" A few even considered going outside – a scary thought.

* Root Cause: Well, it turns out the firewall wanted some "me-time" too and blocked vital API traffic. Can you blame it? Firewalls need self-care too.

## Timeline:

* Detection: 1:00 PM - We received an alert on our monitoring dashboard and thought, "Well, this is unusual."

* Actions Taken: Like Sherlock Holmes chasing a mysterious lead, we immediately dove into server logs. But alas, our initial assumption was as off as a crime drama plot twist. We were searching for a clue in all the wrong places.

* Escalation: At 2:00 PM, we gathered the brave knights of the Network Round Table because suspicion was pointing towards our firewall. We thought, "It's time to exorcise the mischievous rule that haunted us."

* Resolution: At 3:30 PM, after a brief tango with the firewall settings, we finally convinced it to behave – we adjusted the rule, and everything returned to normal. It was as if the firewall had been suffering from stage fright.

## Root Cause and Resolution:

* Cause: Our firewall rule was feeling rebellious and blocked the essential API traffic, as if saying, "I don't want to talk to you anymore."

* Resolution: We had a heart-to-heart with the firewall, explained the importance of open communication, and tweaked the rule to let API traffic flow again. The firewall realized it was overreacting and decided to cooperate 

## Corrective and Preventative Measures:

* Improvements:
    * We're installing a comedy club in the server room. Laughter might lighten the mood.

    * We'll offer the firewall some self-help books on healthy relationships with API traffic.

* Tasks:
    * Implement automated alerts for abnormal firewall behavior – we want to make sure it doesn't get "emo" again.

    * Develop a comprehensive documentation process for firewall rules, complete with pictures and a "happy path" coloring book.
