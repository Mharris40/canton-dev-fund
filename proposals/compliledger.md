## Development Fund Proposal

**Author:** Maranda Harris — Founder, CompliLedger  
**Status:** Submitted  
**Created:** 2026-09-08  
**Label:**  Pick 1 below
- dapp-integration
- wallet-apps
- attestor-pools-daos-multisig
- defi-liquidity
- party-portability-data-resilience
- token-asset-standards
- tokenomics
- onchain-governance
- daml-tooling
- dar-app-management
- canton-protocol-multi-synchronizer
- canton-apis
- node-deployment-operations
- global-synchronizer-scaling
- financial-workflows-composability
- regulatory-compliance

**Champion:** Need Champion

---

## Abstract

Institutional assurance remains heavily manual, fragmented, periodic, and document-driven, with point-in-time assessments repeatedly assembled for audits, regulators, counterparties, and operational workflows. Meanwhile, financial infrastructure is becoming digital, tokenized, programmable, interconnected, and increasingly automated. Assurance must therefore do more than report a past condition: it must respond when the requirements, evidence, or operational conditions supporting a decision change.

CompliLedger is AI-Powered Proof Infrastructure. It brings requirements, target, context, and operational state into a continuous process that determines applicable controls, orchestrates and validates evidence, evaluates evidence sufficiency, and produces deterministic assessments and decisions. AI assists interpretation and evidence orchestration; machine-readable controls and deterministic evaluation logic produce consequential decisions, without forcing a satisfaction judgment when evidence is insufficient. Portable Decision Packages and Canonical Proof Packages make these outputs consumable and machine-verifiable, supporting independent verification and continuously updated assurance.

CompliLedger changes assurance from a periodic reporting exercise into continuously maintained operational assurance. Material changes trigger refreshed evidence and reassessment, producing updated decisions and assurance states that distinguish current support from stale, insufficient, or no-longer-satisfied conditions. Remediation triggers further evaluation rather than leaving an earlier result in place. This shifts manual work toward AI-native processes, periodic assessments toward continuous evaluation, and point-in-time reports toward real-time or near-real-time assurance within defined operating conditions. Ongoing audit readiness and machine-verifiable proof replace repeated audit preparation and static reporting as the intended operating model. Proof is not the entire product: it is the independently verifiable output of a broader process that maintains reusable assurance as conditions change.

Canton is particularly relevant to institutional multi-party financial workflows where privacy, authorization, selective information sharing, deterministic coordination, and composability matter. The proposed application-layer integration connects the assurance supporting financial value with the workflows through which that value moves, allowing authorized parties to consume and independently verify relevant decisions alongside financial activity. Sensitive underlying evidence remains in appropriate protected systems rather than being broadly published to a ledger. CompliLedger complements Canton and authoritative enterprise systems; it does not replace the protocol, systems of record, auditors, or regulators.

CompliLedger already exists as a functioning platform, with an existing limited-control proof of concept, and ProofSync is built. The complete reusable Canton-native implementation does not yet exist. The Development Fund project therefore funds neither the invention of CompliLedger nor the entire private commercial platform. It funds the Canton-native implementation, integration, productionization, security validation, deployment, ecosystem adoption, and post-launch maintenance needed to make its assurance capabilities consumable across Canton. Existing commercial capabilities remain distinct from the new shared integration layer.

The funded output combines reusable Canton-native assurance/proof architecture and continuous reassessment integration with Portable Decision Packages, Canonical Proof Packages, independent verification, and governed workflow consumption. One primary developer SDK, documented interfaces, schemas, and Canton-specific integration for ProofSync, AuditSync, RegSync, and DevSync provide developer and stakeholder access without rebuilding unrelated portal foundations. Two reusable references—Institutional Continuous Assurance and Tokenized RWA / Settlement—will demonstrate changing assurance and reuse of the same infrastructure across institutional workflows. A bounded agentic financial-governance extension will demonstrate authority, delegation, human approval, and execution lineage within that common infrastructure, not as a separate product or the primary project justification.

Canton receives more than a proof format: it gains reusable infrastructure through which participants can consume CompliLedger's AI-native continuous assurance capabilities. Internal teams, clients, counterparties, auditors, regulators, developers, financial applications, and appropriately governed automated workflows can access authorized decisions, proof, and assurance updates. Rather than every participant independently implementing applicability logic, evidence orchestration, continuous evaluation, decision generation, assurance lifecycle management, audit preparation, proof generation, and verification, shared components and interfaces make those capabilities reusable without exposing the private reasoning implementation. Authorized third parties should be able to integrate the supported components, consume packages, verify supported properties, and follow lifecycle changes without a proprietary portal or bespoke employee assistance. Reuse remains conditional on applicability, freshness, context, authorization, and stakeholder requirements; no proof automatically satisfies every regulation or stakeholder.

**Total Funding Request: $385,000 USD.** Based on bottom-up delivery costing, the working program spans approximately 15 months: approximately nine months through accepted production launch, followed by six complete months of bounded post-launch maintenance and ecosystem adoption support. The funded delivery includes external security review, remediation and retesting, production-readiness testing, staged production deployment, documentation, external developer validation, and onboarding. Production launch remains subject to verified Canton deployment requirements and the approved topology. The six-month support period begins only after accepted production launch and is not consumed by implementation delays.
