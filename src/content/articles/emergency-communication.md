---
title: "Emergency Communication: Staying Informed and Reachable When Networks Fail"
description: "How to maintain communications when cell networks are overloaded or down — phones, radios, walkie-talkies, and family contact plans that actually work."
pubDate: 2024-10-15
category: preparedness
tags: [communication, emergency, radio, walkie-talkie, overloaded network, crisis]
image: "/images/communication-crise.jpg"
readingTime: 12
faq:
  - question: "Do texts really get through better than calls during a network overload?"
    answer: "Yes. A voice call creates a continuous connection that occupies bandwidth for its entire duration — typically minutes. A text message transmits in milliseconds and can squeeze through brief gaps in network traffic. During saturation events, text success rates are significantly higher than voice calls. iMessage and WhatsApp work on the same principle (small data packets) and often get through when regular SMS doesn't."
  - question: "Can walkie-talkies be intercepted?"
    answer: "Yes. FRS/GMRS walkie-talkies broadcast on unencrypted public frequencies. Anyone with a radio on the same channel can hear your conversation. For sensitive communications, establish a code system with your group beforehand. For actual encryption, Mesh radios like goTenna Pro offer end-to-end encryption, though at a significantly higher cost."
  - question: "What if I have no battery left and no way to charge?"
    answer: "Priority order: 1) External battery pack if available. 2) Car charger via USB port. 3) Neighbor with power or generator. 4) FEMA or Red Cross relief center — these typically include device charging stations. 5) Local library, fire station, or emergency shelter. The golden rule: always try to keep your phone above 20% charge. Never let it run below 50% if you know a storm or outage is approaching."
  - question: "How do I reach family overseas if internet is down?"
    answer: "If the internet is down but cellular partially works, call directly with the international prefix (+1 for the US, +44 for UK, etc.). If neither works, use an out-of-area contact as a relay — someone in an unaffected region who can pass messages between family members. This is why your family emergency contact plan should include someone outside your immediate area."
  - question: "Does 4G/5G fail before or after home internet during a power outage?"
    answer: "They fail differently. A power outage immediately kills your home internet (router/modem lose power). Cell towers have battery backup, typically 4–8 hours. So during a power outage, you lose WiFi but keep 4G for a window of hours. During a mass-casualty event with millions of people calling simultaneously, cellular saturates faster than landlines. Practically: use cellular for outages, SMS for saturation events."
---

Communication breaks down in the first minutes of an emergency — exactly when you need it most. Networks get jammed, power goes out, and suddenly you can't reach your family, can't get alerts, and don't know what's happening two miles away.

This guide covers the full communication stack: what fails and when, what backup systems to build, and how to establish a family communication plan that works when everything else doesn't.

## Why Normal Communication Fails in Emergencies

**Cell network saturation:** Everyone in an affected area reaches for their phone at the same moment. Networks that handle normal traffic easily can't handle 10x usage. Result: calls fail, texts queue for hours. This is the most common failure mode — it doesn't require any infrastructure damage, just a lot of scared people.

**Power outages:** Your home internet router dies instantly. Cell towers typically run on battery backup for 4–8 hours; some run generators for longer. After that, cellular goes down too.

**Physical infrastructure damage:** Hurricanes, tornadoes, and earthquakes can destroy the towers themselves. After Hurricane Katrina, more than 1,000 cell towers in the Gulf Coast were down. Recovery took weeks in some areas.

**The practical takeaway:** You need communication solutions that don't depend on functioning cell infrastructure.

## Layer 1: Get More Out of Your Smartphone

Before investing in backup equipment, optimize what you have:

**Switch to SMS over voice calls.** Texts require a fraction of the bandwidth and queue successfully. Enable WiFi calling (Settings > Phone > WiFi Calling on iPhone; similar on Android) — it uses your home internet instead of cellular.

**Battery conservation:** Turn off background app refresh, reduce screen brightness to minimum, enable airplane mode and check periodically rather than leaving it on constantly. A smartphone in airplane mode checking for messages every 30 minutes can last 2–3 days.

**Offline maps:** Download your area in Google Maps or Maps.me before an emergency. These work without cell service.

**Emergency alerts:** Ensure Wireless Emergency Alerts (WEA) are enabled on your phone (Settings > Notifications > Government Alerts on most phones). These are broadcast directly to phones in affected areas — they don't require cell network bandwidth.

**The designated out-of-area contact:** Choose one person outside your region as the family relay. Everyone texts or calls them. They relay information between family members. This works because an out-of-area number isn't competing for the same congested local tower.

## Layer 2: Battery Banks and Charging

Your phone is worthless with a dead battery.

**Portable battery bank:** A 20,000–26,800mAh bank charges a smartphone 4–5 times. Enough for 3–4 days if you're conservative. Keep it charged to above 80% — do a monthly check. Anker, Jackery, and RAVPower make reliable options.

**Car charger:** A USB-A or USB-C car charger is a $10–20 backup that uses your car battery. At idle, your car's alternator maintains the battery while charging — 20 minutes of idle time can add significant charge. Keep a quality cable in the glovebox.

**Solar charger:** A 15–25W foldable solar panel can charge a battery bank in direct sunlight. Slower than grid charging but renewable. Useful for 3+ day outages. Keep realistic expectations: a 20W panel needs 5–6 hours of good sun to charge a 20,000mAh bank.

**Hand-crank emergency charger:** Provides enough power to make an emergency call after several minutes of cranking. Not a primary charging solution, but a last-resort backup that weighs nothing.

## Layer 3: Battery-Powered or Hand-Crank Radio

When cell networks fail entirely, AM/FM/NOAA radio is the most reliable public information channel in the United States.

**NOAA Weather Radio** broadcasts 24/7 from over 1,000 stations covering 95% of the country. During emergencies, NOAA broadcasts government emergency alerts, evacuation orders, and situation updates. This is the official emergency broadcast system.

**What to get:** Any radio with NOAA weather band (typically 162.400–162.550 MHz). Hand-crank + solar models let you generate power without batteries. The Midland ER310 and Sangean MMR-99 are well-regarded options ($40–80).

**AM radio for local information:** During major emergencies, local AM stations often broadcast continuous coverage. Keep a list of your local emergency broadcasters.

**Shortwave radio:** More complex but can receive international broadcasts — useful if domestic information is compromised. The Tecsun PL-660 is a capable shortwave radio for under $80.

## Layer 4: Two-Way Radios (Walkie-Talkies)

For communication within your group, neighborhood, or family spread across a few miles, two-way radios provide cell-free communication.

**FRS/GMRS radios** (the standard consumer walkie-talkie): 
- FRS (Family Radio Service): up to 2W, no license required, 22 channels
- GMRS (General Mobile Radio Service): up to 50W, requires FCC license ($35, covers whole family, no test required), significantly more range
- Real-world range: 1–2 miles in urban/suburban environments (despite "35 mile" marketing claims), 3–5 miles line-of-sight in rural/open areas

Good brands: Motorola, Midland, Retevis. A set of 4 radios costs $40–100.

**When walkie-talkies shine:**
- Family members spread across a neighborhood during a local emergency
- Neighborhood emergency groups communicating during power outages
- Parent/teenager communication when phones don't work
- Coordination during evacuation

**Channel plans:** Pre-assign channels before you need them. Channel 1 for family communication, Channel 2 for neighborhood watch, Channel 3 for emergencies. Agree on check-in times.

## Layer 5: Ham Radio (Advanced Option)

Amateur (ham) radio is the most capable communication backup available to civilians. Licensed ham operators can reach across states, countries, or globally using local repeaters and HF bands — without any infrastructure.

**What it requires:** Passing the Technician exam (35 questions, no Morse code required) for local/regional communication. The General license unlocks HF (global) communication. Many communities have ham radio emergency nets (ARES, RACES) that coordinate with emergency management.

**Entry-level setup:** A Baofeng UV-5R handheld (~$25) is an inexpensive way to get started, though quality Yaesu and Kenwood radios are more reliable. For home use, a basic HF station costs $500–2000.

**Local repeaters:** Ham radio uses repeaters — receive-and-retransmit stations on hilltops — to extend handheld radio range dramatically. A 5W handheld can reach 50+ miles through a repeater. Find local repeaters at repeaterbook.com.

## Your Family Communication Plan

Write this down, laminate it, and keep copies in multiple locations. Everyone in the family memorizes or can find this document.

**The plan includes:**

1. **Out-of-area contact:** Name, phone number, backup number. Everyone calls or texts this person if they can't reach other family members directly.

2. **Meeting points:** 
   - Primary: Right outside your home (if you can't shelter in place)
   - Secondary: A neighbor or nearby landmark (if primary is inaccessible)
   - Tertiary: A community location (school, church, community center — 1+ mile away if your neighborhood is affected)

3. **School pickup plan:** Who picks up children if you can't be reached? Who else is authorized? Every school has an emergency contact and authorized pickup policy — make sure yours is current.

4. **Check-in schedule:** At [time], everyone checks in. If no contact within [timeframe], proceed to [next step].

5. **Local emergency broadcasts:** List your local AM station call sign and frequency. List the NOAA Weather Radio frequency for your area.

6. **Radio channel assignments:** If you have walkie-talkies, list the assigned channels here.

7. **Emergency services numbers:** 911 (always), your local non-emergency police line, your local electric/gas utility emergency line, your local emergency management agency.

## Minimum Communication Kit: What to Have at Home

| Item | Purpose | Cost |
|------|---------|------|
| Hand-crank NOAA radio | Emergency alerts without power | $40–80 |
| 20,000mAh battery bank | 4–5 phone charges | $25–50 |
| Car USB charger + cable | Charge from car | $10–20 |
| FRS walkie-talkies (set of 4) | Group communication | $40–100 |
| Printed family contact plan | Works without power | $0 |

**Total:** ~$115–250 for a solid communication backup system.

---

**Related guides:**
- [Family Evacuation Plan: Preparing Before the Emergency](/blog/family-evacuation-plan)
- [72-Hour Emergency Kit: The Complete Family Guide](/blog/72-hour-emergency-kit)
- [Important Documents: How to Protect and Back Them Up](/blog/important-documents)
