# Product Backlog

## Story 1: Calculate simple interest

**As a** user,
**I want** to calculate simple interest given principal, rate, and time,
**So that** I can determine the interest earned on an investment.

### Acceptance Criteria

```gherkin
Given a principal amount, an annual rate, and a time period in years
When I run the simple interest calculator
Then the calculated simple interest is displayed
```

---

## Story 2: Input the principal amount

**As a** user,
**I want** to enter the principal amount,
**So that** it can be used in the interest calculation.

### Acceptance Criteria

```gherkin
Given the calculator is running
When I enter a positive number as the principal
Then the principal is accepted and used in the calculation
```

---

## Story 3: Input the annual rate of interest

**As a** user,
**I want** to enter the annual rate of interest,
**So that** it can be used in the interest calculation.

### Acceptance Criteria

```gherkin
Given the calculator is running
When I enter a positive number as the annual rate of interest
Then the rate is accepted and used in the calculation
```

---

## Story 4: Input the time period in years

**As a** user,
**I want** to enter the time period in years,
**So that** it can be used in the interest calculation.

### Acceptance Criteria

```gherkin
Given the calculator is running
When I enter a positive number as the time period in years
Then the time period is accepted and used in the calculation
```

---

## Story 5: Display the simple interest result

**As a** user,
**I want** to see the calculated simple interest result,
**So that** I know how much interest will be earned.

### Acceptance Criteria

```gherkin
Given valid principal, rate, and time period have been entered
When the calculation is complete
Then the simple interest result is displayed to the user
```
