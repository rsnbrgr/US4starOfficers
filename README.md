# US4starOfficers
This project offers a CSV file that tracks all active duty U.S. four-star military officers, general or admiral, aka "FOGOs" (flag officer / general officer)

I offer this project to the PUBLIC DOMAIN

I launched this project to support a separate project of mine: the BarnOwl Case Study, which operates a Twitter 'bot known as @DaysGWOT that will use the CSV to compare & contrast FOGOs tenures & ages to the length of the Global War on Terror.

Wikipedia maintains a list of 4-star officers at https://en.wikipedia.org/wiki/List_of_active_duty_United_States_four-star_officers and I use it as a secondary source. I verify all data using .mil & .gov as primary sources and I paid close attention to official published biographies. However ... in the specific case of General Wilsbach I chose to accept his birth date from non-govt sources because his birth record was stolen from him during a brutal cyber attack <== I'm not making this up, people

There is also a 27charts.zip file that contains the 27 charts any Air Force officer can consult to see if they fall within (or below) the first standard deviation to make O-10.

_Key descriptions_

"first_name": First name. Spaces allowed in name.

"middle_initial": Middle initial. Blank if no middle name/initial or if not known.

"last_name": Last name.  Spaces allowed in name.

"suffix_name": A suffix e.g. "Jr." or "II". Blank if none.

"position_abbreviation": An abbreviation that represents the element they command and thus an abbreviation for their 4-star position. These abbreviations are NOT unique among the service branches, e.g. "AMC".

"service_branch": Realistically, this field is the officer's service branch, e.g. Army or Navy. In a more legal sense, it's the branch of service that carries the officer on their limited roster of 4-star positions. At this time all valid entries begin with "US". Valid entries include Army (USA), Navy (USN), Marines (USMC), Air Force (USAF), Space Force (USSF), Coast Guard (USCG), and Public Health Service (USPHS). Other uniformed services *do* exist but they don't carry a 4-star position.

"medal_of_honor": yes/no if the officer received the Congressional Medal of Honor.

"purple_heart": yes/no if the officer received the Purple Heart medal.

"academy_grad": yes/no if the officer graduated from a service academy. Includes the Coast Guard Academy. Please don't associate this field to the "service_branch" field because officers sometimes transfer, e.g. to U.S. Space Force (which does not yet boast a Starfleet Academy but I mean c'mon, that's a foregone conclusion).

"birth_date": The officer's date of birth in ISO 8601 format. Blank if unknown.

"o1_date" "o2_date" "o3_date" "o4_date" "o5_date" "o6_date" "o7_date" "o8_date" "o9_date" "o10_date", "o11_date": The officer's effective date of commission or promotion to each rank, O-1 to O-11, in ISO 8601 format. Blank if unknown or if they didn't reach that rank. Note that some branches publish these dates in an officer's bio while others do not.

"retire_date": The officer's effective date of retirement.

"o-10_date2", "retire_date2": The offficer's effective date of promotion to O-10 and retirement after returning to duty from a first retirement. Two officers so far have done this.

"official_bio_url": A URL to the officer's official bio. Not all officers have an official bio for their O-10 position, strange as it may seem. In that case you'll find a link to a previous bio.

"archive_org_bio_url": A URL to the officer's official bio on the Wayback Machine. It won't correlate to the "official_bio_url" field if the officer lacks an official bio for their O-10 position.

"wikipedia_url": a URL to the officer's bio page on Wikipedia.
