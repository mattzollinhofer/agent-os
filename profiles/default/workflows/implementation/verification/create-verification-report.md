Create your final verification report in
`agent-os/specs/[this-spec]/verifications/final-verification.md`.

The content of this report should follow this structure:

```markdown
# Verification Report: [Spec Title]

**Spec:** `[spec-name]` **Date:** [Current Date] **Roadmap Item:** [roadmap-item]
**Verifier:** implementation-verifier **Status:** ✅ Passed | ⚠️ Passed with Issues | ❌
Failed

---

## Executive Summary

[Brief 2-3 sentence overview of the verification results and overall
implementation quality]

---

## 1. Tasks Verification

**Status:** ✅ All Complete | ⚠️ Issues Found

### Completed Slices

- [x] Slice 1: [Title]
  - [x] Task 1.1
  - [x] Task 1.2
- [x] Slice 2: [Title]
  - [x] Task 2.1

### Incomplete or Issues

[List any tasks that were found incomplete or have issues, or note "None" if all
complete]

---

## 2. Documentation Verification

**Status:** ✅ Complete | ⚠️ Issues Found

### Implementation Documentation

- [x] Slice 1 Implementation:
      `implementations/1-[slice-name]-implementation.md`
- [x] Slice 2 Implementation:
      `implementations/2-[slice-name]-implementation.md`

### Verification Documentation

[List verification documents from area verifiers if applicable]

### Missing Documentation

[List any missing documentation, or note "None"]

---

## 3. Roadmap Updates

**Status:** ✅ Updated | ⚠️ No Updates Needed | ❌ Issues Found

### Updated Roadmap Items

- [x] [Roadmap item that was marked complete]

### Notes

[Any relevant notes about roadmap updates, or note if no updates were needed]

---

## 4. Test Suite Results

**Status:** ✅ All Passing | ⚠️ Some Failures | ❌ Critical Failures

### Test Summary

- **Total Tests:** [count]
- **Passing:** [count]
- **Failing:** [count]
- **Errors:** [count]

### Failed Tests

[List any failing tests with their descriptions, or note "None - all tests
passing"]

### Notes

[Any additional context about test results, known issues, or regressions]
```

{{workflows/commit-changes}}
