# STDF
## Description
Standard test data format (STDF), the most commonly used data format for datalogging storage of semiconductor test information, is a binary format produced by automatic test equipment (ATE). Data in STDF can be converted to ASCI, where it becomes ASCII Test Data Format (ATDF), which is easier for a human to read than a binary format. STDF does not specify a database architecture.

Teradyne first introduced STDF in 1985. In 2008, a special interest group in SEMI, Collaborative Alliance for Semiconductor Test (CAST), was tinkering with STDF. Teradyne granted SEMI a license in 2010 to improve and manage the standard. The standards for STDF are defined by the STDF V4 specification. CAST did produce an addition to STDF, the SEMI G91 — STDF memory fail datalog in 2011, to provide a common format for memory fail datalog specification and synchronization information used in volume diagnostics applications for memories. However, SEMI’s Automated Test Equipment Global Technical Committee — which is the voting committee on test standards — in 2019 disbanded its task force on STDF and approved work on a new standard to succeed STDF, called RITdb, which CAST is now working on.

STDF is efficient in saving the data near real time as the test program is running, but the data structure is not efficient for reporting purposes, according to YieldHub. The data needs to be organized into a different data structure designed to be efficient for reporting. The STDF also represents a static view of the data and is useful for analysis after the tests are completed, but the data needs to be cleaned because different tool vendors and test engineers handle the collection and input of the data differently. The new RITdb standard will make adaptive test possible.
(origin: [Description of the Standard Test Data Format (STDF)](https://semiengineering.com/knowledge_centers/test/data-analytics/standard-test-data-format-stdf/))

## Specification
Specification: [Standard Test Data Format (STDF) Specification - Version 4](STDF/std-spec.pdf)

