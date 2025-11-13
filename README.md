# Claude Hub - WordPress Development Agents & Skills

A collection of specialized Claude agents and reusable skills for WordPress development, focusing on code review, accessibility, performance optimization, and security.

## Overview

This repository contains Claude agents and skills designed to help with WordPress development tasks. Agents are autonomous assistants that can perform specific tasks, while skills are reusable knowledge bases that agents can reference.

## Agents

### WordPress Code Reviewer
**File:** `agents/wordpress-code-reviewer.md`

Expert WordPress code reviewer that automatically reviews WordPress code changes. Specializes in:
- WordPress coding standards compliance
- Security vulnerability detection (XSS, SQL injection, CSRF)
- Performance optimization
- Best practices validation

Use proactively after any WordPress theme, plugin, or core modification.

### WordPress Accessibility Specialist
**File:** `agents/wordpress-accessibility-specialist.md`

Ensures WordPress sites meet accessibility standards (WCAG 2.1 AA/AAA). Expertise in:
- WCAG compliance analysis
- ARIA implementation
- Keyboard navigation
- Screen reader compatibility
- Accessible WordPress block patterns

### WordPress Performance Optimizer
**File:** `agents/wordpress-performance-optimizer.md`

Optimizes WordPress site performance through:
- Database query optimization
- Asset loading strategies
- Caching implementation
- Core Web Vitals improvement
- Performance auditing and recommendations

## Skills

Skills are reusable knowledge bases that agents can reference during their work.

### WordPress Security Patterns
**Location:** `skills/wordpress-security-patterns/`

Comprehensive security patterns and code examples for:
- SQL injection prevention
- XSS escaping requirements
- CSRF/nonce verification
- Authentication & authorization
- Input sanitization
- File upload security

### WordPress Accessibility Patterns
**Location:** `skills/wordpress-accessibility-patterns/`

Common accessibility patterns and implementations for WordPress development.

### WordPress Site Speed Auditor
**Location:** `skills/wordpress-site-speed-auditor/`

Performance auditing tools and techniques for WordPress sites.

## Usage

These agents and skills are designed to work with Claude's agent framework. Reference them in your Claude configuration or invoke them programmatically based on your development workflow.

## Contributing

Contributions are welcome! When adding new agents or skills:
1. Follow the existing file structure and naming conventions
2. Include clear documentation of capabilities and use cases
3. Reference existing skills where applicable
4. Test thoroughly with WordPress codebases

## License

MIT License - See LICENSE file for details
