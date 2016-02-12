# Making reliable distributed systems in presence of software errors

**Author**: Joe Armstrong
**Date**: December 2003
**URL**: http://ftp.nsysu.edu.tw/FreeBSD/ports/distfiles/erlang/armstrong_thesis_2003.pdf

## Notes

- Introduction:
  - History of Erlang and brief description of team and events which happened at
    Ericsson.
  - Thesis outline.
- Architectural Model
  - Describing problem domain, philosophy and architecture.
  - Focused mostly on "concurrency oriented programming language" (COPL).
    - Describing key koncepts like process isolation, location transparency,
      message passing and protocols.
  - Defining system, language, library and application requirements.
- Erlang
  - Complete, but still concise description of Erlang programming language.
  - Describes also part of standard libraries.
- Programming Techniques
  - Description of techniques which are particularly useful when working with
    Erlang.
    - Abstracting out concurrency.
    - Maintaining the Erlang view of the world.
    - The Erlang view of errors.
    - Intentional programming.
- Programming Fault-tolerant Systems
  - Describing in details concepts like supervision, process isolation etc.
  - It describes also what is an error, and why we should tackle the problem
    differently that we approached all the time.
- Building an Application
  - Describing concept of behaviors and describing most useful ones.
- OTP
  - Describing what OTP is, why it is important to have it in Erlang.
- Case Studies
  - Meat of whole thesis. Amazing summary of various projects written in Erlang
    with a lot of details about maintenance, designing and implementation.
    - Most interesting chapter for me because of different approaches, different
      techniques used and various problems solved with use of specific
      technology and particular implementation.
- APIs and Protocols
  - Interesting chapter about theory of protocols and way of verifying them
    based on contracts provided on both sides and doing automated contracts
    verification.
    - Probably most theoretical and impressive chapter in terms of ideas and
      innovative approach to contract verification.
- Conclusions
  - Thesis conclusions and summing up achievements.
- Appendix: UBF
  - Alternative form of communication to XML and JSON, which is very efficient
    and still relies on pure binary form - Universal Binary Format.
  - Very interesting concept, Erlang uses something similar to communicate
    across multiple nodes in the cluster.
