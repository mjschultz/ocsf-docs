# Frequently Asked Questions
##



at least initially in no particular order


##

##

##

##

## How does OCSF relate to STIX?
OCSF and STIX are compatible.

Structured Threat Information Expression (STIX™)
is a open-source language and serialization format
used to exchange cyber threat intelligence (CTI).
For more info on STIX, see
[this info](https://oasis-open.github.io/cti-documentation/stix/intro.html)
or the
(spec itself](https://docs.oasis-open.org/cti/stix/v2.1/csprd01/stix-v2.1-csprd01.html)

Add something here on how OCSF/STIX are complimentary

##
=======
## How does OCSF relate to OSSEM?
draft text for here

Open Source Security Events Metadata (OSSEM)
is a community-led project focused
primarily on the documentation,
standardization and modeling of security event logs.
See [OSSEM repo](https://github.com/OTRF/OSSEM)


##

##

##

##

##

##

##

##

##

##

##
=======
## What is OCSF?
Open Cybersecurity Schema Framework (OSCF)
is an open-source effort to create a common schema
for security events across the cybersecurity ecosystem.

See [this whitepaper](./Understanding OCSF.pdf)
for more info.

=======
See [this whitepaper](https://github.com/sparrell/ocsf-docs/blob/main/Understanding%20OCSF.pdf)
for more info.

## What Problems does OCSF solve for?
One of the primary challenges of cybersecurity analytics
is that there is no common and agreed-upon format
and data model for logs and alerts.
As a result, pretty much everyone in the space creates
and uses their own format and data model
(IE sets of fields).  
There are *many* such models that exist,
including some open ones like
STIX, OSSEM, and the Sigma taxonomy.
The challenge to date is that none of these
models have become widely adopted by practitioners
for logging and event purposes,
and thus it requires a lot of manual work
in order to derive value.
This poses a challenge to
detection engineering, threat hunting,
and analytics development,
not to mention AI – as Rob Thomas said,
“There is no AI without IA”.
Despite the issues this causes in the industry,
there has been no significant progress on the problem space,
because until now there has been lack of a “critical mass”
of major players willing to tackle the problem head-on, and
with efforts like this, timing is everything.
With OCSF,
we are now at a moment where we have 
that critical mass as well
as a real willingness to tackle these challenges.

## How can I contribute to OCSF?
See the
[OCSF Contribution Guide](https://github.com/ocsf/ocsf-schema/blob/main/CONTRIBUTING.md)

## What is OCSF Governance Model?
See [OCSF Governance](https://github.com/ocsf/governance/blob/main/Governance.md)
