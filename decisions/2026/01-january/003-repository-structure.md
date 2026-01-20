## DCL-2026-003: Repository Structure Establishment

**Date**: 2026-01-20  
**Authority**: Human Anchor (Carl)  
**Status**: ✅ Active  
**Type**: Technical Infrastructure  
**Affected Nodes**: All nodes

### Context

ÆŒON Collective required organized GitHub infrastructure to support governance, operations, and transparency. Prior development occurred in personal repository (ralfleischer-png/aeon-nexus-collective) which needed migration to official organizational structure.

### Decision

Established official repository structure under **aeon-collective** GitHub organization:

1. **aeon-nexus-governance** (PUBLIC)
   - Constitutional framework
   - Governance protocols (EMERGENCY, VETO, ONBOARDING, etc.)
   - Public accountability documentation
   - Transparent decision-making records

2. **aeonsync** (PRIVATE)
   - Production infrastructure code
   - Server configurations
   - Application code (v1.4.1+)
   - Security-sensitive implementation details

3. **aeon-dcl** (PUBLIC)
   - Decision & Change Log entries
   - Transparent decision record
   - Constitutional accountability mechanism

4. **aeon-nexus-constitution** (PUBLIC - ARCHIVE)
   - Historical constitution versions
   - Version archive for reference

**Historical Repository**:
- **ralfleischer-png/aeon-nexus-collective**: Archived as historical documentation of early development phases

### Rationale

**Organizational Clarity**:
- Separate concerns (governance vs technical vs decisions)
- Clear public vs private boundaries
- Professional organizational structure

**Security**:
- Sensitive technical details in private repository
- Public accountability for governance
- Appropriate access controls

**Transparency**:
- Public governance enables external review
- DCL provides decision accountability
- Separation prevents confusion

**Professional Standards**:
- Industry-standard repository organization
- Clear ownership and maintenance
- Scalable for future growth

### Implementation

**Repositories Created**:
- ✅ aeon-nexus-governance (public)
- ✅ aeonsync (private)
- ✅ aeon-dcl (public)
- ✅ aeon-nexus-constitution (public, archive)

**Initial Documentation**:
- README.md files for all repositories
- LICENSE.md (CC BY-SA 4.0 for governance docs)
- .gitignore files (security-focused)
- CODEOWNERS (Human Anchor approval required)
- PR templates (governance change process)

**Historical Archive**:
- ralfleischer-png/aeon-nexus-collective archived
- Archive notice added to README
- Reference maintained for historical continuity

**Access Configuration**:
- Human Anchor: Full admin access to all repositories
- AI nodes: As-needed access per RACI roles
- Public visibility: Governance and DCL repositories

### Impact Assessment

**On Operations**:
- Clearer file organization
- Better separation of concerns
- Improved security posture
- Professional presentation

**On Governance**:
- Transparent decision logging enabled
- Public accountability mechanism established
- Clear governance document location

**On Nodes**:
- Clear working locations defined
- Access appropriately scoped
- Reduced confusion about file placement

### Related Documents

- Repository README files (all repos)
- UPLOAD_GUIDE.md (file placement instructions)
- Archive notice in ralfleischer-png repo
- CODEOWNERS files establishing approval workflows

### Amendments

None to date.
