# lendme
  2 A P2P lending platform which allows lenders and borrowers bid for the best deal.Lenders and borrowers are anonymous to each other , they lend each other based on their credibility rather than identity. 
  
# Architecture
    - REST API Backend
    - Vue Js for UI
    - Docker for Pakcaging
    - Kubernetes for Deployment
# Build & Setup

# Use Cases
- Any User can register themselves with a valid Unique Identifier (SSN,PAN etc.,).
- Users should be limited to create only one account.
- Users contact details(mobile,Email etc) should be validated with a 2F authentication.
- All users can lend aswell borrow money from others.
- There should be a max cap on the amount a user can borrow at a time. There is no limit for lending though.
- Also there should be max cap on the total amount a user is on debt in a period.
- User's documents should be stored securely .It should never be shared to any other users
- A independent third party can 

# Exposed Models
- Users 
    - Name
    - Unique ID 
    - Rating
    - Debt
- LendRequest
- Accounts
- 

# REST Endpoints

- /

# Test Cases
