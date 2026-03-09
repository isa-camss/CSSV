# Core Standards and Specifications Vocabulary (CSSV)

[![License](https://img.shields.io/badge/License-EUPL%201.2-blue.svg)](https://joinup.ec.europa.eu/collection/eupl/eupl-text-eupl-12)
[![Latest Release](https://img.shields.io/badge/version-2.0.0-green.svg)](https://interoperable-europe.ec.europa.eu/collection/common-assessment-method-standards-and-specifications-camss/solution/core-standards-and-specifications-vocabulary-cssv)

## 📋 Overview

The **Core Standards and Specifications Vocabulary (CSSV)** is a CAMSS vocabulary used for the information exchange related to standards and specifications amongst software solutions, and for the description of themselves amongst other specifications. It is a key element for the continuous development of the ELIS, as it allows to list specifications in a machine-readable format.

CSSV is a specification that assures and controls quality of data and information at the basis of standards and specifications for the design and development of interoperable systems supporting Digital Public Services.

## 🎯 What Problem Does CSSV Solve?

When organisations implement digital public services, they need to:
- Share information about which standards and specifications they're using
- Understand dependencies between different standards
- Assess the suitability of standards for specific contexts
- Ensure interoperability across systems and borders

CSSV addresses these challenges by providing:

✅ **Standardised terminology** for describing standards and specifications  
✅ **Machine-readable format** that enables automated processing  
✅ **Semantic interoperability** through reuse of established vocabularies (DCAT, FOAF, etc.)  
✅ **Extensibility** to accommodate domain-specific needs  

## 🏗️ Design Principles

CSSV follows two fundamental principles:

### 1. **Consistent Reuse**
Respect and reuse already existing and commonly agreed interpretation of concepts and ontologies (e.g., DCAT, CCCEV, FOAF etc.), thus facilitating semantic interoperability. The methodological approach followed for the development of the CSSV reuses the following ontologies and vocabularies:
- **Data Catalogue Vocabulary (DCAT)**
- **Friend of a Friend (FOAF)**
- **The W3C Organization Ontology**
- **DCMI Metadata Terms (DCTerms)**
- **The Profiles Vocabulary (PROF)**
- **Schema.org**

### 2. **Separate constraints**
Isolate technical and business limitations and rules as much as possible to ensure flexibility and cost-saving quality of the implementation and maintenance of the “core” vocabulary.

## 📦 What's in This Repository

This repository contains the formal specification and implementation files for CSSV:

```
CSSV/
│── uml                                   # The CSSV UML.
│   ├── CSSV_UML_v2.0.0.drawio          # The CSSV UML in drawio format.
│   └── CSSV_UML_v2.0.0.png             # The CSSV UML in png format.
├── CAMSS_info v9.0.0.pdf                 # Set of informative documents about CAMSS.
├── CSSV Specification v2.0.0.pdf         # The CSSV v2.0.0 specification in pdf format.
├── README.md                             # The github readme of the CSSV.
├── cssv_shapes.ttl                       # The CSSV in RDF format.
└── cssv_tbox.ttl                         # The CSSV in RDF format.
```

## 🌍 Relationship to Other Initiatives

### SEMIC
The CSSV, even though is evolved and maintained by the CAMSS Action, it is part of the Core Vocabularies that SEMIC is providing. All of them, including the CSSV are labelled as Interoperable European Solutions (IES)

## 📚 Additional and Learning Resources

- **CSSV on Interoperable Europe Portal**: [Core Standards and Specifications Vocabulary (CSSV)](https://interoperable-europe.ec.europa.eu/collection/common-assessment-method-standards-and-specifications-camss/solution/core-standards-and-specifications-vocabulary-cssv)
- **CSSV in HTML format**: [CSSV Vocabulary in HTML](https://isa-camss.github.io/CSSV/)
- **CAV on Interoperable Europe Portal**: [Core Assessment Vocabulary (CAV)](https://interoperable-europe.ec.europa.eu/collection/common-assessment-method-standards-and-specifications-camss/solution/core-assessment-vocabulary-cav)
- **CAMSS Welcome Page**: [CAMSS on Interoperable Europe](https://interoperable-europe.ec.europa.eu/collection/common-assessment-method-standards-and-specifications-camss)
- **"Introduction to Core Vocabularies" course**: [Core Vocabularies course on Interoperable Europe Academy](https://academy.europa.eu/courses/introduction-to-core-vocabularies)

## 📄 License

CSSV is released under the **European Union Public Licence (EUPL) v1.2**.

You are free to use, modify, and distribute this vocabulary in accordance with the EUPL terms. See the [LICENSE](https://eupl.eu/1.2/en/) file for details.

## 🤝 Contributing

CSSV has been developed through public consultation with input from various stakeholders. We welcome feedback and contributions:

1. **Report Issues**: Use GitHub Issues to report bugs, suggest improvements, or request clarifications
2. **Discuss Use Cases**: Share your implementation experiences and domain-specific needs
3. **Submit Changes**: Fork the repository and submit pull requests for enhancements
4. **Extend for Your Domain**: Create domain-specific extensions and share your approach

## 📧 Contact

For questions, feedback, or collaboration opportunities:
- Open an issue in this repository
- Visit the [Interoperable Europe Portal](https://interoperable-europe.ec.europa.eu/)
- Contact the CAMSS team through official channels: DIGIT-CAMSS@ec.europa.eu
- Join the CAMSS community discussions

## 🔄 Version History

- **v2.0.0** (Latest): Current stable release
- **v1.4.1**: Bug-fix release of CSSV removing references to OWL redefinitions of external terms
- **v1.4.0**: Alignment with SEMIC style guide practices
- **v1.3.0**: Added enhanced metadata properties
- **v1.2.0**: Improved alignment with DCAT
- **v1.1.0**: Extended with assessment-related concepts
- **v1.0.0**: Initial public release

See the full release history [here](https://interoperable-europe.ec.europa.eu/collection/common-assessment-method-standards-and-specifications-camss/solution/core-standards-and-specifications-vocabulary-cssv/releases)

---

**Maintained by**: DIGIT.B2  
**Last Updated**: 2026  
**Status**: Active development and maintenance
