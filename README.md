# Allocator Bookkeeping Repository for Helmsman Tech

## Allocator JSON Link

[Helmsman Tech Allocator JSON](https://github.com/filecoin-project/Allocator-Registry/blob/main/Allocators/helmsman.json)

## Client Diligence

Helmsman Tech verifies clients to establish trust, prevent sybil attacks, and confirm data ownership for Fil+ compliance.

- Require photo ID, facial photo via Gitcoin Passport (score >20) for KYC verification within 3 business days.
- Enterprises submit registration, licenses, signatory proof via Synaps.io ($100) or virtual meetings for KYB.
- Cap new GitHub IDs (<2 months) at 50 TiB DataCap; cross-check via `datacapstats.io` to prevent sybil attacks.
- Store KYC/KYB documents, ownership contracts on GitHub for Governance Team audits and transparency.
- Review client applications for data ownership via contracts, IP registrations; flag discrepancies for clarification.

## Description of Data Diligence

Helmsman Tech ensures datasets meet Fil+ scope, legal compliance, and public open data standards through rigorous verification.

- Verify data ownership with contracts, IP registrations, or digital signatures; cross-check via Synaps.io or virtual meetings.
- Confirm legal compliance (e.g., PII) via client attestations and legal consultations; store documentation on GitHub.
- Sample 10% of public dataset sectors using Booster-Bitswap, ipfs-car to validate content matches client claims.
- Test retrievability with Spark protocol, targeting ≥75% success within ≤20ms; audit via `datacapstats.io` weekly.
- Require justification for duplicate datasets; publish CID audits, data preparation scripts on GitHub for transparency.

## Short Description of Pathway for Clients

Helmsman Tech empowers enterprises, developers, and learners to onboard high-quality public/private data to Filecoin. With robust KYC/KYB, transparent compliance, and diverse SP distribution, we ensure trust, scalability, and impactful storage.

## Contact Info

- **Enterprise Email**: zhangruxia@grandhelmsman.com
- **Website**: [http://www.grandhelmsman.com/](http://www.grandhelmsman.com/)
- **Slack**: URXSQ78QG (Filecoin Slack)
- **GitHub**: [Acumes](https://github.com/Acumes)
- **Support**: Open issues on [Acumes/Helmsman-Bookkeeping](https://github.com/Acumes/Helmsman-Bookkeeping)

## Detailed Allocator Policies, Procedures, and Requirements

Helmsman Tech adheres to Fil+ governance for transparent DataCap allocation, targeting 40 PiB in 12 months.

- Clients submit applications via GitHub issues with KYC/KYB, project details, and SP distribution plans.
- Review applications within 3 business days; request clarifications via GitHub issue threads for transparency.
- Allocate DataCap in tranches (5%, 10%, 20%, 40%) up to 12 PiB per client, based on compliance.
- Require 5+ replicas across 5+ SPs in ≥4 regions to ensure redundancy and decentralization.
- Monitor compliance weekly using AC Bot, `datacapstats.io`; expire unused DataCap after 3 months.

## Metrics and KPIs for Pathway Success

Helmsman Tech tracks metrics to ensure pathway success and Fil+ compliance.

1. **Data Retrievability Score (RSR)**  
   - **Definition**: Percentage of public datasets retrievable within 20ms via SPARK.  
   - **Measurement**: Weekly SPARK checks on `datacapstats.io`.  
   - **Success (6 Months)**: Average RSR >75%; no SP <70% for 2 weeks.  
   - **Rules**:  
     - Ensure SPs maintain unsealed dataset copies for high retrievability and compliance.  
     - Audit RSR weekly; flag SPs with low scores for immediate review.  
     - Suspend DataCap for SPs failing RSR compliance after 2 weeks.  
     - Publish bi-monthly RSR reports on GitHub for Governance audits.  
   - **Reporting**: Bi-monthly GitHub RSR reports.

2. **DataCap Utilization Rate**  
   - **Definition**: Percentage of DataCap used for deals within 3 months.  
   - **Measurement**: Track deals via `datacapstats.io`.  
   - **Success (6 Months)**: 10 PiB encapsulated, >80% utilization rate.  
   - **Rules**:  
     - Allocate DataCap in tranches up to 12 PiB per client based on usage.  
     - Monitor utilization weekly; flag clients with <50% usage for review.  
     - Expire unused DataCap after 3 months; reclaim for reallocation to active clients.  
     - Publish monthly utilization reports on GitHub for transparency and audits.  
   - **Reporting**: Monthly GitHub utilization updates.

3. **Client and Dataset Diversity**  
   - **Definition**: Unique clients, dataset types, and SPs across ≥4 regions.  
   - **Measurement**: Log clients, datasets, SPs on GitHub; verify via `datacapstats.io`.  
   - **Success (6 Months)**: 10+ clients, 5+ dataset types, 5+ SPs, ≥4 regions.  
   - **Rules**:  
     - Onboard 10+ clients with diverse public/private datasets to enhance network utility.  
     - Distribute deals across 5+ SPs in ≥4 regions for decentralization.  
     - Limit single dataset type to <50% of total DataCap to ensure diversity.  
     - Publish quarterly diversity reports on GitHub for Governance audits.  
   - **Reporting**: Quarterly GitHub diversity reports.

## Risk Mitigation Strategies

Helmsman Tech employs strict measures to protect the pathway and Fil+ program integrity.

- Secure multisig wallet (f2qmtkrgnk3evrrhzqq6if7tyj7ywav4tof53wrhy) with Ledger hardware; restrict access to authorized signatories.
- Limit new GitHub IDs to 50 TiB DataCap; cross-check via `datacapstats.io` to prevent sybil attacks.
- Audit clients bi-monthly for sector padding via SPARK; suspend DataCap for non-compliance after 3 weeks.
- Use `check bot` to monitor DataCap usage in real-time; flag suspicious activity for review.
- Publish all decisions, audit logs, and compliance reports on GitHub for community transparency.

## Dispute Resolutions

Helmsman Tech resolves disputes transparently to ensure fairness and accountability.

- Address internal disputes via email (zhangruxia@grandhelmsman.com) within 1-2 business days; document resolutions on GitHub.
- Handle external disputes via Filecoin Foundation tracker within 21 days; provide evidence (deal records, KYC/KYB).
- Require evidence from all parties; suspend DataCap for non-compliant clients during dispute resolution.
- Publish dispute outcomes on GitHub, respecting client privacy unless public disclosure is mandated.

## Compliance Audit Check

Helmsman Tech ensures clients and SPs meet Fil+ and pathway-specific requirements.

- Monitor weekly via AC Bot, `datacapstats.io` for deal-making, RSR >75%, and SP compliance.
- Verify SP KYB (business license, datacenter proof) for non-vetted SPs before approving allocations.
- Audit >75% DataCap utilization before granting new tranches; flag non-compliant clients for review.
- Conduct random 10% sector checks via SPARK, Booster-Bitswap to verify data integrity and compliance.

## Application Details

- **Submission Deadline**: July 11, 2025, via [apply.allocator.tech](https://apply.allocator.tech/).
- **Correct Application**: [Allocator-Registry/pull/1030](https://github.com/filecoin-project/Allocator-Registry/pull/1030).
- **Erroneous Application**: [Allocator-Registry/pull/1028](https://github.com/filecoin-project/Allocator-Registry/pull/1028) (request closure).
- **Prior Application**: [filecoin-project/filecoin-plus-large-datasets#2090](https://github.com/filecoin-project/filecoin-plus-large-datasets/issues/2090).
- **Community Engagement**: Attend bi-weekly Governance calls ([calendar link](https://calendar.google.com/calendar/embed?src=c_k1gkfoom17g0j8c6bam6uf43j0%40group.calendar.google.com&ctz=America%2FLos_Angeles)).
