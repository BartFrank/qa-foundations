# Test Strategy — Web Application (Sanity & Functional)

## 1. Objective
Validate that the main user-facing functionality works as expected
before production release.

This strategy focuses on:
- Core user flows
- Functional correctness
- Real-user perspective

Out of scope:
- Edge cases
- Security testing
- Performance testing
- Destructive testing

---

## 2. Testing Approach
Manual functional testing performed from a user perspective.

The goal is to:
- Click through the application naturally
- Validate expected behavior
- Identify broken flows or confusing behavior
- Provide fast feedback to developers

---

## 3. Test Scope

### In Scope
- Navigation
- Forms
- Main actions
- State changes
- Error handling (basic)

### Out of Scope
- Fuzzing
- Invalid input abuse
- Load or stress testing

---

## 4. Test Environment
- Browser-based testing
- Desktop (Chrome / Firefox)
- Development environment

---

## 5. Reporting
Issues will be reported in real time via chat, including:
- Steps to reproduce
- Expected behavior
- Actual behavior
