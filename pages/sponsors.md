---
layout: page
title: Our Sponsors
permalink: /sponsors/
---
## Our Sponsors

We would like to take a moment to thank you for your interest in supporting the Midwest Regional Collegiate Cyber Defense Competition. This is a very special event for us and we strive to make each competition better than the last. We rely on sources of support to help us grow and reach our goal of making the Midwest CCDC a top notch event and a great experience for the participating students. The Midwest CCDC has a positive impact on the educational institutions on multiple levels. Participants gain hands-on experience securing systems, handling business demands, and prioritizing their tasks while working on a mix of operating systems, networking equipment, and hardware components.  Faculty and staff take CCDC observations and experiences back to their campuses and make changes to improve their curriculums.

The Midwest CCDC event has grown considerably since the first regional event was held in 2005.  In 2006 we had 8 schools participating at our regional level—in the 2011 season, we had increased to 30 schools competing at the state and regional levels.  In 2013, 44 schools participated as CSSIA also hosted qualifying CCDC for the Northeast and Southwest Regions. The Midwest CCDC represented nearly half of the schools involved nationally.  Combined, CSSIA hosted 76 schools in qualification CCDC in 2013. The 2013 Midwest CCDC regional competition included 8 state winners and two wildcard teams that traveled to Moraine Valley Community College to compete for the trophy and title of Regional Collegiate Cyber Defense Champions. Rose-Hulman, winning the 2013 MW-CCDC championship, moved on to compete in the National CCDC Championship in San Antonio, demonstrating the Midwest’s strength in the Cyber Security education space by placing third nationally.  It is very exciting for us to see the interest level picking up within the various educational institutions and to have the increased participation across the region and nation. We truly believe this is a trend that will continue.

Sponsors and supporters play a very large role in CCDC events, whether it be the donation of money, time, hardware, software, or other in-kind donations. The students that come to the Midwest CCDC are truly the best and the brightest. We like to challenge the students with the latest and greatest technologies. Without sponsorships this would be nearly impossible. We also actively seek vendor partnerships working to find ways to introduce new products and technologies to the competition. At each competition we encourage recruiting by sponsors to link the participants with potential employers. Our sponsors are invited and encouraged to attend this unique opportunity to meet and recruit.  We will continue to expand this portion of the competition.

Thank you again for your interest in the Midwest Regional Collegiate Cyber Defense Competition.  We hope that you will find this to be a valuable event and worthy of your support.

{% for s in site.data.sponsors %}
- **{{ s.name }}** ({{ s.tier }} sponsor) — [website]({{ s.url }})
{% endfor %}
