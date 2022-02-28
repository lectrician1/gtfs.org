# GTFS.org

Source code for [gtfs.org](https://gtfs.org/). 

This site was built using [MkDocs](https://www.mkdocs.org/), a static site generator, and [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/), a technical documentation theme for MkDocs.

## Editing site

To propose a feature, content addition, or UI/UX improvement, open an [issue](https://github.com/MobilityData/gtfs.org/issues/new) or [pull request](https://github.com/MobilityData/gtfs.org/pulls) on this repository. To edit site content, see instructions below.

## Editing site content

The GTFS Documentation Platform is based on open source content pulled from various repositories. To propose edits to content, make an issue or pull request in the respective source-of-truth repository found in the table below.

### Sources of truth & licenses

| gtfs.org | Source of truth | License |
| - | - | - |
| / | TBD |  | 
| /background/ | TBD  | | 
| /schedule/ | TBD | | 
| /schedule/reference/ | https://github.com/google/transit/blob/master/gtfs/spec/en/reference.md | Apache License 2.0 | 
| /schedule/best-practices/ | https://github.com/MobilityData/GTFS_Schedule_Best-Practices | CC BY 3.0 | 
| /schedule/examples/ | TBD | |
| /schedule/examples/example-feed/ | TBD | |
| /schedule/examples/data-examples/ | TBD | | 
| /schedule/changes/ | https://github.com/google/transit/blob/master/gtfs/CHANGES.md | Apache License 2.0|  
| /schedule/changes/process | https://github.com/google/transit/blob/master/gtfs/CHANGES.md | Apache License 2.0 |  
| /schedule/changes/guiding-principles | https://github.com/google/transit/blob/master/gtfs/CHANGES.md | Apache License 2.0 |  
| /schedule/changes/revision-history | https://github.com/google/transit/blob/master/gtfs/CHANGES.md | Apache License 2.0 | 
| /realtime/ | TBD | |
| /realtime/reference/ | https://github.com/google/transit/blob/master/gtfs-realtime/spec/en/reference.md | Apache License 2.0 |
| /realtime/proto/ | https://github.com/google/transit/blob/master/gtfs-realtime/proto/gtfs-realtime.proto | Apache License 2.0 | 
| /realtime/best-practices/ | https://github.com/MobilityData/GTFS_realtime_Best-Practices | CC BY 3.0 |
| /realtime/feed-entities/ | https://github.com/google/transit/blob/master/gtfs-realtime/spec/en/feed-entities.md | Apache License 2.0 | 
| /realtime/trip-updates/ | https://github.com/google/transit/blob/master/gtfs-realtime/spec/en/trip-updates.md | Apache License 2.0 | 
| /realtime/service-alerts/ | https://github.com/google/transit/blob/master/gtfs-realtime/spec/en/service-alerts.md | Apache License 2.0 | 
| /realtime/vehicle-positions/ | https://github.com/google/transit/blob/master/gtfs-realtime/spec/en/vehicle-positions.md | Apache License 2.0 | 
| /realtime/examples/ | TBD | | 
| /realtime/feed-examples/ | https://github.com/google/transit/blob/master/gtfs-realtime/spec/en/example | Apache License 2.0 | 
| /realtime/code-examples/ | TBD | | 
| /realtime/changes/ | https://github.com/google/transit/blob/master/gtfs-realtime/CHANGES.md | Apache License 2.0 | 
| /realtime/process/ | https://github.com/google/transit/blob/master/gtfs-realtime/CHANGES.md | Apache License 2.0 | 
| /realtime/guiding-principles/ | https://github.com/google/transit/blob/master/gtfs-realtime/CHANGES.md | Apache License 2.0 | 
| /realtime/revision-history/ | https://github.com/google/transit/blob/master/gtfs-realtime/CHANGES.md | Apache License 2.0 | 
| /realtime/extensions/ | https://github.com/google/transit/blob/master/gtfs-realtime/CHANGES.md | Apache License 2.0 | 
| /resources/*/ | https://github.com/CUTR-at-USF/awesome-transit/blob/master/README.md | CC0 1.0 Universal | 
| /extensions/ | TBD | |
| /about/ | TBD | |

## Updating site structure

If a [source of truth](#source-of-truth-licenses) is specified, the site content is pulled, cleaned programatically, and given a directory destination in the repository. If a source of truth is unspecified, the content lives in this repository. The site structure is manually built in `mkdocs.yml` under `nav: `.

## Maintenance

- Script for site maintenance will be published soon.

## License

Except as otherwise noted, the content of this site is licensed under the [Creative Commons Attribution 3.0 License](https://creativecommons.org/licenses/by/3.0/), and code samples are licensed under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).


