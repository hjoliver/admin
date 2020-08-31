# Cylc Project VC 1 September 2020

*(Meeting notes in italics)*

## Cylc-7

- [7.8.x Milestone](https://github.com/cylc/cylc-flow/milestone/82)
- (last month's GUI sorting bug fixed)
- (Release not a high priority; let's back-port Cylc 8 fixes as we go,
  then make a release later on)

## Cylc-8

- [Development timeline from 
  workshop](https://cylc.github.io/cylc-admin/feb2020-workshop-report#tentative-development-timeline)

Progress:
- SoD merged (follow-ups from proposal now Issues; priorities TBD)
- Platforms merged
- infinite tree not needed! (delta updates made plain tree perform well)
- UI filtering almost ready
- CLI GraphQL almost ready
- async scan (including stopped flows) almost ready

Do we need another alpha release? (meh)

Beta release MVP October/November?
- UI
  - performant tree view with filtering
  - integrated mutations
  - scan stopped flows, and allowing starting them
- UIS
  - event-driven n-distance datastore (n=1 in scheduler)
  - load older tasks from disk
  - start stopped flows
- Other
  - `rose suite-run` migration (suite installation etc.)
  - CLI via GraphQL
  - task status naming changes (incl. xtrigger PR)

- UIS subservices, cross-user functionality, etc...

Nice to have (for beta release):
- new graph view - (hierarchical layout less important now?)
- Cylc 8 migration guide with all breaking changes listed
- cross-user functionality
- delta-driven TUI (needs homemade GraphQL subscriptions at the scheduler)

 
## cylc/cylc-flow

- [Current PRs](https://github.com/cylc/cylc-flow/pulls)
- [Open Questions](https://github.com/cylc/cylc-flow/issues?q=is%3Aopen+is%3Aissue+label%3Aquestion)
- platforms: ready for review


## AOB?

## Next Meeting?

- TP to arrange for early October