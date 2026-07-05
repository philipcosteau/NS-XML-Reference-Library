# API Reference Library Update Log

**Date:** 2026-07-05 14:07:28  
**API Version:** 13 (as reported by the `nation/name` shard)  [API version 13 adds World Assembly proposal, resolution, and WASec Opinion metadata. It is backward-compatible with version 12: existing fields retain their previous meanings and formats, and heavier nested data remains opt-in.]

**Method:**  
All public shards were fetched using `curl` with a descriptive User‑Agent, respecting the 50‑requests‑per‑30‑seconds rate limit by inserting a 0.7‑second delay between calls. The responses were compressed on‑the‑fly as `*.xml.gz`.

## Shard Counts

| Category | Number of Shards |
|----------|------------------|
| Nation   | 69         |
| Region   | 42         |
| World    | 24         |
| WA       | 30        |
| **Total**| 165 |

## Shards Fetched

### Nation shards
`admirable,animal,animaltrait,answered,banner,banners,capital,category,census,census_scale1,crime,currency,customcapital,customleader,customreligion,dbid,deaths,demonym,demonym2,dispatches,dispatchlist,endorsements,factbooklist,factbooks,firstlogin,flag,founded,foundedtime,freedom,fullname,gavote,gdp,govt,govtdesc,govtpriority,happening,income,industrydesc,influence,influenceum,lastactivity,lastlogin,leader,legislation,majorindustry,motto,name,notable,notables,nstats,policies,poorest,population,publicsector,recensus,region,religion,richest,scvote,sectors,sensibilities,tax,tgcancampaign,tgcanrecruit,type,wa,wabadges,wcensus,zombie,`

### Region shards
`banlist,banner,bannerurl,bannery,census,censusranks,dbid,delegate,delegateauth,delegatevotes,dispatches,embassies,embassyrmb,factbook,flag,founded,foundedtime,founder,frontier,gavote,governor,governortitle,happenings,history,lastmajorupdate,lastminorupdate,lastupdate,magnetism,messages,name,nations,numnations,numwanations,officers,poll,power,recruiters,scvote,tags,wabadges,wanations,zombie,`

### World shards
`banner,census,censusdesc,censusid,censusname,censusranks,censusscale,censustitle,dispatch,dispatchlist,faction,factions,featuredregion,happenings,latesteventid,nations,newnationdetails,newnations,numnations,numregions,poll,regions,regionsbytag,tgueue,`

### World Assembly shards
`council2_delegates,council2_dellog,council2_delvotes,council2_happenings,council2_lastresolution,council2_members,council2_numdelegates,council2_numnations,council2_opinions,council2_proposal,council2_proposals,council2_resolution,council2_resolution_current,council2_voters,council2_votetrack,council3_delegates,council3_dellog,council3_delvotes,council3_happenings,council3_lastresolution,council3_members,council3_numdelegates,council3_numnations,council3_opinions,council3_proposal,council3_proposals,council3_resolution,council3_resolution_current,council3_voters,council3_votetrack,`

## Notes
- Example nation used: **testlandia**  
- Example region used: **the_north_pacific**  
- Both General Assembly (council=3) and Security Council (council=2) were queried.  
- This update corresponds to the current live API (no `v=` parameter was supplied, so the latest version is used).  
- For a full changelog of the NationStates API, refer to the [official documentation](https://www.nationstates.net/pages/api.html).  
- Generated automatically by the update script on 2026-07-05.
