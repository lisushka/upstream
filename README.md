# Upstream Accessibility: A Contributor's Guide

## Presentations

- **linux.conf.au 2022**, 2022-01-15 (open captions, [transcript](transcript.md), CC BY-NC-SA 4.0)

## References

### My world through public transport

#### Yarra Trams

* [The Victorian Auditor's report on Yarra Trams accessibility](https://www.audit.vic.gov.au/report/accessibility-tram-services?section=)
* [Yarra Trams Accessibility Statement](https://yarratrams.com.au/accessibility)
* [Route guides](https://yarratrams.com.au/route-guides/) (includes locations of stops with platforms)
* [Yarra Trams Accessibility Action Plan](https://yarratrams.com.au/media/1550/yarra-trams-accessibility-action-plan-2019-to-2022-final.pdf) | [Plain Language Version](https://yarratrams.com.au/media/1543/easy-english-accessibility-action-plan-190802.pdf)

#### Metro Trains

* [Train Station Accessibility Features](https://www.metrotrains.com.au/station-accessibility-features/)
* [Accessible Boarding](https://www.metrotrains.com.au/station-accessibility-features/boarding/)
* [Metro Trains Accessibility Action Plan](https://ds12k1658w1f2.cloudfront.net/wp-content/uploads/2019/08/J004357-AAP-Booklet-%C6%92_INT.pdf)

### Access to public utilities

#### Robles v. Domino's Pizza LLC

##### Court documents

* [Robles' original complaint in the US District Court for the Central District of California](https://www.courtlistener.com/docket/4615111/1/guillermo-robles-v-dominos-pizza-llc/)
* [The original verdict of the district court, dismissing Robles' case](https://www.courtlistener.com/docket/4615111/42/guillermo-robles-v-dominos-pizza-llc/)
* [Summary and full text (PDF) of the Ninth Circuit decision overturning the lower court's verdict](https://law.justia.com/cases/federal/appellate-courts/ca9/17-55504/17-55504-2019-01-15.html)
* [Domino's Pizza petition for writ of certiorari in the US Supreme Court (PDF)](http://www.supremecourt.gov/DocketPDF/18/18-1539/102950/20190613153319483_DominosPetition.pdf)
* [Supreme Court release denying certiorari in the case, effectively agreeing with the judgement of the circuit court (PDF, page 18)](https://www.supremecourt.gov/orders/courtorders/100719zor_m648.pdf)
* [Lower court ruling granting summary judgement to Mr. Robles (PDF)](https://www.adatitleiii.com/wp-content/uploads/sites/121/2021/06/Dominos-MSJ-Order.pdf)

##### News articles

* [Supreme Court hands victory to blind man who sued Domino’s over site accessibility](https://www.cnbc.com/2019/10/07/dominos-supreme-court.html), **Tucker Higgins**, *CNBC*, 2019-10-07
* [Domino Pizza’s Website Violated the Americans With Disabilities Act (ADA)](https://blog.ericgoldman.org/archives/2021/06/domino-pizzas-website-violated-the-americans-with-disabilities-act-ada-robes-v-dominos.htm), **Eric Goldman**, *Technology and Marketing Law Blog*, 2021-06-27

### `gov.uk` domains

* [GOV.UK landing page](https://www.gov.uk/)

**NOTE:** The claim that I make about the `.gov.uk` TLD being the most accessible due to not using web frameworks is based on information that's several years out of date.  I have obtained screenshots of page archives from the era where this was true, but as of 2015, UK government websites have been rolled into the landing page above, which uses Javascript and jQuery.  `.gov.uk` remains one of the most accessible second-level domains on the Web - I ran a random sample of its pages through the [WAVE](https://wave.webaim.org/) accessibility checker, and all but one had 0 detectable errors.  (This is in contrast to `.gov.au`, where all five of the randomly-selected sites that I ran had errors, with three having more than 10.)

### Frameworks on the Web

* [The WebAIM Million](https://webaim.org/projects/million/): a survey of the top 1 million sites on the Web by Alexa rank
* [Tailwind CSS](https://tailwindcss.com/)
* [Tailwind UI](https://tailwindui.com/)
* Tailwind Components:
  - [Headless UI](https://headlessui.dev/)
  - [HeroIcons](https://heroicons.com/)

### Just use dark mode, it'll be fine

* [CapFriendly](https://www.capfriendly.com/)
* [Chicago Blackhawks](https://www.nhl.com/blackhawks/) (**NOTE:** while I use the name of the team's mascot in the talk to avoid making the explanation harder to understand with euphemisms, there is a [significant controversy](https://en.wikipedia.org/wiki/Chicago_Blackhawks_name_and_logo_controversy) about whether First Nations names and iconography should be used in professional sport at all; I agree with the views of Black Hawk's descendants and the Sac and Fox Nation that the name and logo should be retired)

### The process of upstream accessibility

* [How to avoid being an accessibility grinch (hosted on Medium; has accessibility problems)](https://uxdesign.cc/how-to-avoid-being-an-accessibility-grinch-85d124440d52) | [accessible version](https://sheribyrnehaber.com/how-to-avoid-being-an-accessibility-grinch/)

### Accessibility testing tools

* [WebAIM WAVE](https://wave.webaim.org/)
* [axe accessibility checking tools](https://www.deque.com/axe/)
* [A list of other tools for accessibility testing](https://www.w3.org/WAI/ER/tools/)  (**NOTE:** WAVE and axe are the point-in-time checker and browser extension, respectively, that I prefer.  The tools in this longer list are of varying quality.  However, some of them are designed to detect particular accessibility issues, or assist with manual testing; this is why the list is included here.  I recommend researching the organisations that produce these tools, and seeking recommendations for particular use-cases from people with disabilities.  Specifically, watch out for tools on this list that are produced by [accessibility overlay companies](https://overlayfactsheet.com/).)

## The Shoulders of Giants

* [Jess Budd](https://jessbudd.com/)
* [Katie Macke](https://github.com/asleepysheepy)
* [Sheri Byrne-Haber](https://sheribyrnehaber.com/sheri-byrne-haber-bio/)

## Images

* [**Melbourne metro**](https://tinyurl.com/upstream-07), eGuide Travel (CC BY 2.0)

[Back to main talks repo](https://github.com/lisushka/talks)
