# Alfred Agent Platform v2 Documentation

*Last Updated: 2025-05-10*  
*Owner: Documentation Team*  
*Status: Active*

Welcome to the Alfred Agent Platform v2 documentation repository. This repository contains comprehensive documentation for all aspects of the platform, including its architecture, agents, workflows, APIs, and operational guides.

## Documentation Highlights

### High-Priority Documentation

All high-priority documents have been successfully migrated and are available:

- [System Architecture](/architecture/system-architecture.md)
- [Agent Core Framework](/architecture/agent-core.md) 
- [A2A Protocol](/api/a2a-protocol.md)
- [Social Intelligence Agent](/agents/social-intelligence-agent.md)
- [Financial-Tax Agent](/agents/financial-tax-agent-migrated.md)
- [Legal Compliance Agent](/agents/legal-compliance-agent-migrated.md)
- [Agent Implementation Guide](/agents/guides/agent-implementation-guide-migrated.md)
- [Niche Scout Workflow](/workflows/niche-scout-workflow-migrated.md)
- [Seed to Blueprint Workflow](/workflows/seed-to-blueprint-workflow-migrated.md)
- [Infrastructure Overview](/infrastructure-crew/overview.md)
- [Deployment Guide](/operations/deployment-guide.md)
- [Master Project Plan](/project/master-plan.md)
- [Technical Design Guide](/project/technical-design.md)

### Getting Started

If you're new to the Alfred Agent Platform v2, we recommend starting with these documents:

1. [Documentation System Summary](/documentation-system-summary.md) - Overview of the documentation system
2. [System Architecture](/architecture/system-architecture.md) - Understand the platform architecture
3. [Agent Implementation Guide](/agents/guides/agent-implementation-guide-migrated.md) - Learn how to implement agents

## Documentation Structure

```
/docs
├── agents/                  # Agent documentation
│   ├── catalog/             # Agent catalog and index
│   ├── guides/              # Implementation guides
│   ├── core/                # Core system agents
│   ├── personal/            # Personal & Family tier agents
│   ├── business/            # Solo-Biz tier agents
│   └── domain/              # Domain-specific agents
│
├── workflows/               # Workflow documentation
│   ├── catalog/             # Catalog of all workflows
│   ├── by-agent/            # Workflows organized by agent
│   └── by-project/          # Workflows organized by project
│
├── project/                 # Project-level documentation
│   ├── master-plan.md       # Project plan, timeline
│   └── technical-design.md  # Technical architecture
│
├── api/                     # API documentation
│   └── a2a-protocol.md      # Agent-to-agent communication
│
├── architecture/            # Architecture documentation
│   └── system-design.md     # System design details
│
├── templates/               # Document templates
│   ├── agent-template.md    # Template for agent docs
│   ├── workflow-template.md # Template for workflow docs
│   ├── project-template.md  # Template for project docs
│   └── archive-template.md  # Template for archived docs
│
├── governance/              # Documentation governance
│   ├── standards/           # Documentation standards
│   ├── processes/           # Documentation processes
│   └── ai-tools/            # AI tool configuration
│
├── examples/                # Example documents
│
├── tools/                   # Documentation tools
│   ├── doc_migration_inventory.py # Migration helper
│   └── doc_validator.py     # Validation script
│
├── infrastructure-crew/     # Infrastructure documentation
├── operations/              # Operations documentation
│
├── migration-plan.md        # Migration planning
├── github-reference-guide.md # GitHub-specific references
└── documentation-system-summary.md # System overview
```

## Documentation Principles

1. **Single Source of Truth** - Each piece of information should exist in exactly one place
2. **Clear Organization** - Documentation is structured logically and consistently
3. **Completeness** - Documentation covers all necessary aspects of the subject
4. **Accuracy** - Information is correct, up-to-date, and verified
5. **Discoverability** - Information is easy to find through navigation and search

## Navigation

- [Agent Catalog](/agents/catalog/agent-catalog.md)
- [Workflow Catalog](/workflows/catalog/workflow-catalog.md)
- [Service Catalog](/services/service-catalog.md)
- [Templates](/templates)
- [Governance Documents](/governance)
- [Examples](/examples)
- [GitHub Reference Guide](/github-reference-guide.md)
- [Documentation System Summary](/documentation-system-summary.md)
- [Migration Plan](/migration-plan.md)
- [Migration Dashboard](/tools/outputs/migration_dashboard_updated_5.md)
- [Migration Tracking](/tools/outputs/migration_tracking_updated_6.md)

## Migration Status

This documentation repository is the result of a comprehensive migration project:

- Overall Completion: 20%
- Phase 2 Completion: 65%
- High-Priority Documents: 13/13 (100% complete)

For detailed migration status, see:
- [Migration Tracking](/tools/outputs/migration_tracking_updated_6.md)
- [Migration Dashboard](/tools/outputs/migration_dashboard_updated_5.md)
- [Phase 2 Progress Report](/tools/outputs/phase2-progress-updated-2.md)

## Working with AI Tools

This documentation is designed to work well with AI coding tools. See the [AI tools guide](/governance/ai-tools/README.md) for instructions on using different AI assistants with this documentation.

For GitHub-specific references and optimal prompts for AI tools, see the [GitHub Reference Guide](/github-reference-guide.md).

## Contributing

### Documentation Standards

When contributing to this documentation, please follow the [Documentation Standards](/governance/standards/documentation-standards.md) and use the appropriate templates for new content:

- [Agent Template](/templates/agent-template.md)
- [Workflow Template](/templates/workflow-template.md)
- [Project Template](/templates/project-template.md)
- [Archive Template](/templates/archive-template.md)

For detailed contribution guidelines, see [Documentation Process](/governance/processes/documentation-process.md).

## Contact

For questions about this documentation, contact the Documentation Team.