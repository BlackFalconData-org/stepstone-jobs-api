# StepStone Jobs API

Search job listings from StepStone, TotalJobs and related job boards via a developer-friendly API.

Available on:
- **Apify:** https://apify.com/blackfalcondata/stepstone-jobs-feed
- **RapidAPI:** https://rapidapi.com/black-falcon-data-black-falcon-data-default/api/stepstone-jobs

## Example request

Run the actor via the Apify API:

POST https://api.apify.com/v2/acts/blackfalcondata~stepstone-jobs-feed/runs

Example input:
```json
{
  "query": "data engineer",
  "geo": "DE",
  "maxResults": 10
}
```

## Example response
```json
{
  "count": 10,
  "results": [
    {
      "title": "Senior Data Engineer",
      "company": "Siemens AG",
      "location": "Munich, Bavaria",
      "datePosted": "2026-03-07T01:19:42+01:00"
    }
  ]
}
```

## Supported portals

- stepstone.de
- stepstone.at
- stepstone.be
- stepstone.nl
- totaljobs.com
- cwjobs.co.uk
- jobsite.co.uk
- milkround.com
- careerstructure.com
- cityjobs.com
- caterer.com
- pnet.co.za
- jobs.ie
- and 5 more UK vertical portals

## Documentation

- **Apify actor:** https://apify.com/blackfalcondata/stepstone-jobs-feed
- **RapidAPI:** https://rapidapi.com/black-falcon-data-black-falcon-data-default/api/stepstone-jobs

## Related

- [Company Jobs Tracker](https://github.com/BlackFalconData-org/company-jobs-tracker-api) — track new and removed job listings per company with change detection
- [Arbeitsagentur Jobs Feed](https://github.com/BlackFalconData-org/arbeitsagentur-jobs-feed) — extract job listings from Germany's federal employment portal
- [Indeed Jobs Feed](https://github.com/BlackFalconData-org/indeed-jobs-feed) — extract job listings from Indeed
- [Glassdoor Jobs Feed](https://github.com/BlackFalconData-org/glassdoor-jobs-feed) — extract job listings from Glassdoor
