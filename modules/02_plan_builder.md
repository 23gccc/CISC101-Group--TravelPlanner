Change Log (2025-11-22) : Refined Module 02 based on AI critique: specified budget limit, activity details, cost limit.

### **Module 2 — Plan Builder (Options → Days)**

Candidate Activities
Create a short list of candidate activities (e.g., attractions, restaurants, parks). Each activity now includes:

* Type (museum, park, restaurant, etc.)

* Estimated duration (hours)

* Cost range (low, mid, high)

* Distance (from lodging or previous activity)

* Indoor/Outdoor flag

* Operating hours / booking needed

* Neighborhood/area

* Suitability (mobility, dietary, pace preferences)

### **Daily Plan Loop**
For each day:

* Initialize envelopes

* Time cap: total active hours based on user’s preferred pace (relaxed, balanced, fast).

* Budget target: daily spend aligned with budget style (affordable, mid-range, luxury).

* Morning activity (near lodging)

* Pick: activity open in morning hours, short transfer, aligned with interests.

* Add alternate: indoor option in same neighborhood.

* Midday activity + lunch

* Pick: activity close to morning stop, different theme.

* Lunch: restaurant matching dietary needs and budget, near activity.

* Add alternate: indoor backup (e.g., café, gallery).

* Afternoon activity (theme contrast)

* Pick: activity with different theme/energy level, feasible transfer.

* Add alternate: indoor backup if primary is outdoor.

* Evening restaurant or optional event

* Pick: dinner or event, check booking flag and budget.

* Add alternate: cheaper restaurant of similar cuisine or casual venue.

### **Transport and clustering**

Default mode: walk, transit, or rideshare depending on distances and mobility needs.

Cluster activities by neighborhood to minimize transfers.

Validate envelopes

Time check: if over cap, shorten lunch or pick nearer stop.

Budget check: if over target, swap meal or lower-cost activity.

### **Output per Day**
Primary plan: Morning, Midday + Lunch, Afternoon, Evening slots with times and brief transfer notes.

Alternates: One backup per slot, clearly labeled.

Reminders: Booking recommended items (do not simulate bookings).
