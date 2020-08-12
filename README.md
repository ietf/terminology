# Inclusive Terminology in IETF Documents

Some choices of terminology that might seem harmless to some members of the community have painful connotations for others.  To ensure that the Internet standards process is open and welcoming for everyone, we should avoid such terminology in favor of more inclusive (and often more accurate!) options.

Here are some of the most common problematic terms and some suggested alternatives:

| Avoid                                 | Better                                            |
|:--------------------------------------|:--------------------------------------------------|
| Whitelist                             | allowlist                                         |
| Blacklist	                            | blocklist, denylist                               |
| Master/slave                          | leader/follower, primary/replica, active/standby  |
| Grandfathered	                        | legacy status                                     |
| Gendered terms (e.g., guys)           | Folks, people, you all, y'all                     |
| Gendered pronouns (e.g., he/him/his)  | They, them, their                                 |
| Man in the middle                     | On-path attacker, impersionation attack           |
| Man hours	                            | Person hours, engineer hours, staff hours         |
| Sanity check                          | Quick check, confidence check                     |
| Crazy                                 | Unexpected, surprising, puzzling                  |
| Dummy value                           | Placeholder value, sample value                   |

This list is obviously not comprehensive.  In general, authors and reviewers
should try to make sure they use language that is inclusive along a few
dimensions:

* Gender
* Age
* Ability
* Ethnicity

More background can be found in [this Internet-Draft](https://tools.ietf.org/html/draft-knodel-terminology-03).

## References

Sometimes IETF documents need to refer to terminology from older IETF documents
or non-IETF documents.  Such terminology might not meet the standards for
inclusiveness that we would apply to IETF documents today.  In such cases, the
author of the new IETF document should map old terms to new, better terms.  [For
example](https://tools.ietf.org/html/draft-rescorla-tls-rfc8446-bis-00):

> Note: the key derivation labels use the string "master" even though
> the values are referred to as "main" secrets.  This mismatch is a
> result of renaming the values while retaining compatibility.

## Background: Elsewhere on the Internet

The IETF is not alone in trying to make its terminology more inclusive.  Some
peer organizations have published guidelines for writing more inclusive
documentation, for example:

* [Twitter](https://twitter.com/TwitterEng/status/1278733305190342656)
* [Google](https://developers.google.com/style/inclusive-documentation)
* [Chromium](https://chromium.googlesource.com/chromium/src/+/master/styleguide/inclusive_code.md#racially-neutral)

Several of the examples above are drawn from these guides, and they also include
more detailed considerations.

Other organizations working on the same goal include:

* [NIST](https://www.politico.com/news/2020/06/25/agency-ends-use-technology-terms-racist-associations-339880)
* [RedHat](https://www.redhat.com/en/blog/making-open-source-more-inclusive-eradicating-problematic-language)
* [IBM](https://www.ibm.com/downloads/cas/2DZELQ4O)
* [Splunk](https://www.splunk.com/en_us/blog/leadership/biased-language-has-no-place-in-tech.html)
* [GitLab](https://gitlab.com/gitlab-org/gitlab/-/issues/221164)
* [UK National Cyber Security Centre](https://www.ncsc.gov.uk/blog-post/terminology-its-not-black-and-white)
