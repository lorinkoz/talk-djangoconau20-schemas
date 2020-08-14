# Outline

Intro

-   Who am I
-   The multi-million dollar idea
-   Multi-tenancy

Schemas

-   Basics
-   PostgreSQL schemas
-   Database backend + router
-   Management commands

Short-term challenges

-   Shared models vs. tenant specific models
-   Users + sessions
-   Content types (low priority)
-   Moving models between schemas

Mid-term challenges

-   Speed of tenant creation (cleaning up migrations + cloning)
-   Cross-tenant aggregations
-   Scalability of migrations
-   Zero downtime deployments

Long-term challenges

-   Scalability of tables
-   Sharding
-   Changing database architecture

Outro

-   Closing remarks
-   Invitation to contribute to open source

# Intro inspiration

https://www.reddit.com/r/django/comments/hyiseb/why_i_use_django/
https://www.reddit.com/r/django/comments/dmufzm/whats_wrong_with_my_multitenancy_approach/

# Disclaimers

-   Talk is not focused in managing a RDBMS, only on the Django side of things

# References

-   https://influitive.io/our-multi-tenancy-journey-with-postgres-schemas-and-apartment-6ecda151a21f
-   https://stackoverflow.com/questions/44524364/postgresqls-schemas-for-multi-tenant-applications
-   https://dev.to/kspeakman/breaking-postgres-with-too-many-tables-4pg0
-   https://scalegrid.io/blog/postgresql-connection-pooling-part-1-pros-and-cons/
-   https://www.2ndquadrant.com/en/blog/how-do-postgresql-security_barrier-views-work/

-   https://www.pgcon.org/2013/schedule/events/595.en.html
-   https://gist.github.com/shon/36c59af03f8c3c24da55925d01286c16

-   https://www.citusdata.com/blog/2016/08/10/sharding-for-a-multi-tenant-app-with-postgres/
-   http://www.craigkerstiens.com/2012/11/30/sharding-your-database/
-   https://instagram-engineering.com/sharding-ids-at-instagram-1cf5a71e5a5c

-   https://www.forbes.com/sites/theyec/2014/06/20/the-seven-startup-metrics-you-must-track/
-   https://medium.com/@jproco/how-startups-measure-success-before-they-generate-revenue-4f42d4d7a076
-   https://medium.com/@ninalovelace/how-to-measure-your-startups-success-34b8aad7516b
