# Upgrade Extraction - User Customization Recovery

## 🎯 **Mission**
Systematically extract user customizations from the 6 core templates in `core/` directory to preserve personalized content before system upgrades.

## 🔍 **Extraction Protocol**

### **Phase 1: Scan Core Templates**

Analyze each core template for content that replaced HTML comment placeholders:

**Target Files**:
- `core/00-PROJECT-REQUIREMENTS.md`
- `core/01-AI-COLLABORATION-CORE.md`
- `core/02-SESSION-MANAGEMENT.md`
- `core/03-PROBLEM-SOLVING-METHODS.md`
- `core/04-LEARNING-CAPTURE.md`
- `core/05-SYSTEM-DEPLOYMENT.md`

**Extraction Pattern Recognition**:
```markdown
# BEFORE (Original Template)
<!-- Core project purpose and advanced practitioner value -->

# AFTER (User Customized)
Building an AI-powered content management system for technical documentation
```

### **Phase 2: Create Extraction Directory**

```bash
# Create temporary extraction workspace
mkdir -p upgrade-temp/
```

### **Phase 3: Generate Indexed Extraction Files**

For each core template, create numbered extraction file:

**File Naming Convention**:
- `upgrade-temp/01-project-requirements-customizations.md`
- `upgrade-temp/02-ai-collaboration-customizations.md`
- `upgrade-temp/03-session-management-customizations.md`
- `upgrade-temp/04-problem-solving-customizations.md`
- `upgrade-temp/05-learning-capture-customizations.md`
- `upgrade-temp/06-system-deployment-customizations.md`

**Extraction Format**:
```markdown
# [Template Name] - User Customizations
*Extracted: [Date/Time]*

## Section: [Heading Name]
### Original Placeholder:
```
<!-- Original comment placeholder text -->
```

### User Customization:
```
[User's actual content that replaced the placeholder]
```

### Restoration Location:
- **File**: `core/[filename].md`
- **Line Range**: Lines [X-Y]
- **Block Reference**: `^[reference-id]` (if applicable)

---

[Repeat for each customization found]
```

### **Phase 4: Generate Restoration Index**

Create `upgrade-temp/user-customizations-index.md`:

```markdown
# User Customizations Index
*Generated: [Date/Time]*

## 🎯 **Extraction Summary**
- **Templates Scanned**: 6 core files
- **Customizations Found**: [Number]
- **Total Customized Content**: [Estimate in lines/chars]

## 📋 **Customization Inventory**

| Template | Customizations | Priority | Restoration Complexity |
|----------|----------------|----------|----------------------|
| 00-PROJECT-REQUIREMENTS | [Count] | High | [Simple/Medium/Complex] |
| 01-AI-COLLABORATION | [Count] | High | [Simple/Medium/Complex] |
| 02-SESSION-MANAGEMENT | [Count] | Medium | [Simple/Medium/Complex] |
| 03-PROBLEM-SOLVING | [Count] | Medium | [Simple/Medium/Complex] |
| 04-LEARNING-CAPTURE | [Count] | Low | [Simple/Medium/Complex] |
| 05-SYSTEM-DEPLOYMENT | [Count] | Low | [Simple/Medium/Complex] |

## 🔧 **Restoration Roadmap**

### **Critical Customizations** (Restore First)
1. **Project Mission & Architecture** (`00-PROJECT-REQUIREMENTS.md`)
   - Project purpose, technical stack, performance targets
   - **Impact**: Core system identity and technical foundation

2. **Working Relationship DNA** (`01-AI-COLLABORATION-CORE.md`)
   - Collaboration patterns, communication style, trust framework
   - **Impact**: AI partnership effectiveness

### **Important Customizations** (Restore Second)
3. **Session Context & Active Work** (`02-SESSION-MANAGEMENT.md`)
   - Current session focus, working state, interruption recovery
   - **Impact**: Immediate productivity continuity

4. **Custom Problem-Solving Patterns** (`03-PROBLEM-SOLVING-METHODS.md`)
   - Domain-specific approaches, validation methods
   - **Impact**: Systematic methodology effectiveness

### **Optional Customizations** (Restore Last)
5. **Learning Insights** (`04-LEARNING-CAPTURE.md`)
   - Breakthrough entries, innovation documentation
   - **Impact**: Knowledge preservation and community contribution

6. **Deployment Configuration** (`05-SYSTEM-DEPLOYMENT.md`)
   - Environment setup, tool configuration
   - **Impact**: System setup and operational efficiency

## 📝 **Detailed Restoration Guide**

[Generated automatically for each customization with specific instructions]
```

### **Phase 5: Validation & Next Steps**

**Extraction Validation Checklist**:
- [ ] All 6 core templates scanned
- [ ] `upgrade-temp/` directory created with indexed files
- [ ] User customizations identified and documented
- [ ] Restoration locations mapped with precision
- [ ] Priority restoration order established
- [ ] `user-customizations-index.md` generated

**Success Confirmation**:
```markdown
✅ **Extraction Complete**
- **Templates Processed**: [6/6]
- **Customizations Found**: [Number] across [X] templates
- **Extraction Files**: Ready in `upgrade-temp/`
- **Restoration Index**: Generated with priority roadmap

**Next Step**: Review `upgrade-temp/user-customizations-index.md` and proceed with upgrade knowing your customizations are preserved and mapped for restoration.
```

## 🎯 **Advanced Practitioner Optimization**

**Key Extraction Priorities**:
1. **Project-specific content** - Technical stack, architecture, domain requirements
2. **Collaboration preferences** - Communication style, working relationship DNA
3. **Active session context** - Current work, focus areas, session state
4. **Custom methodologies** - Domain-specific problem-solving approaches
5. **Learning artifacts** - Breakthrough insights, innovation documentation

**Restoration Strategy**:
- **Immediate**: Critical project and collaboration configurations
- **Short-term**: Session context and active work restoration
- **Long-term**: Learning insights and methodology customizations

---

**Usage**: Copy this prompt to AI and execute to systematically preserve user customizations before upgrading the V3 Session Continuity Kit core templates.