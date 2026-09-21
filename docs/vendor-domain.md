# Woven Stories — Vendor Domain

## 1. Overview

**Woven Stories** is a multi-vendor marketplace for fiber arts and crafts.

Vendors can sell products such as:

* Yarn
* Fabrics
* Embroidery supplies
* Knitting and crochet supplies
* Patterns
* Craft kits
* Tools
* Handmade products

Woven Stories supports two types of vendors:

1. Individual Artisan
2. Business


## 2. Vendor Types

### 2.1 Individual Artisan

An individual who sells their own handmade products or craft supplies through Woven Stories.

Examples:

* Independent yarn dyer
* Knitter
* Crocheter
* Embroidery artist
* Fiber artist

### 2.2 Business

A registered business that sells fiber arts and craft products through Woven Stories.

Examples:

* Yarn shop
* Craft supply store
* Textile company
* Handmade goods business

The information and documentation required during registration may differ depending on the vendor type.


# 3. Vendor Registration

A vendor must complete the registration and verification process before they can sell products on Woven Stories.

## 3.1 Registration Flow

Select Vendor Type
        ↓
Enter Basic Information
        ↓
Verify Email and Phone
        ↓
Create Account
        ↓
Enter Seller Additional Information
        ↓
Provide Required Documents
        ↓
Provide Payout Information
        ↓
Submit Seller Application
        ↓
Admin Review
        ↓
   ┌────┴─────┐
   ↓          ↓
Approved    Rejected
   ↓          ↓
Can Sell    Can Resubmit
Products

## 3.2 Select Vendor Type

The vendor selects one of the supported vendor types:

* Individual Artisan
* Business

The registration process collects information appropriate to the selected vendor type.

## 3.3 Basic Information and Contact Verification

The vendor provides:

* Email address
* Phone number

Both email and phone number must be verified.

## 3.4 Account Creation

After completing the required account information and verification steps, the vendor creates their account using a password.

## 3.5 Seller Information

The vendor provides additional information required for the seller application.

Depending on the vendor type, this may include:

### Individual Artisan

* Legal name
* Address
* Contact information
* Required identity information
* Required verification documents

### Business

* Legal business name
* Business registration information
* Business address
* Authorized representative
* Required business documents

The vendor also provides the information required to receive marketplace payouts.

## 3.6 Submit Application

The vendor reviews the provided information and submits the seller application for administrative review.

## 3.7 Administrative Review

An administrator reviews the seller application and supporting information.

The application can be:

* **Approved** — the vendor becomes eligible to sell products.
* **Rejected** — the vendor can correct the required information and resubmit the application.
* **Blocked** — the vendor is prevented from continuing the application because of serious policy, security, or verification concerns.


# 4. Vendor Status

Vendor status represents the seller's current lifecycle state.

### Registered

The vendor has created an account but has not yet completed or submitted a seller application.

### InReview

The vendor has submitted a seller application and it is currently being reviewed.

### Active

The seller has been approved and is currently allowed to sell products on Woven Stories.

### Suspended

The seller's selling privileges have temporarily been disabled.

A suspended seller cannot sell products until the suspension is resolved.

### Blocked

The seller is permanently prevented from operating as a seller on Woven Stories.

### Closed

The seller relationship has been permanently closed, either by the seller or by Woven Stories.


# 5. Seller Verification

Seller verification is separate from the seller's overall status.

A seller may remain **Active** while their verification is being renewed.

For example:

Seller Status:
Active

Verification Status:
ReverificationRequired

This means:

> The seller can continue selling, but must complete reverification within the required period.


## 5.1 Verification Statuses

Possible verification states include:

* NotStarted
* Pending
* Verified
* ReverificationRequired
* ReverificationInReview
* Rejected
* Expired


# 6. Reverification

Woven Stories may require an existing seller to complete reverification.

Reverification can be triggered by:

* Periodic verification requirements
* Expiration of previous verification
* Changes to important seller information
* Changes to business information
* Changes to payout information
* Changes in the seller's risk profile
* Unusual marketplace activity
* Security-related events
* Additional verification requirements following a review

Reverification does not automatically mean that the seller has violated a rule.

It means that Woven Stories requires additional or updated verification information.

## 6.1 Reverification Flow

Active Seller
      ↓
Reverification Required
      ↓
Seller Continues Selling
      ↓
Seller Submits Required Information
      ↓
Reverification In Review
      ↓
   ┌─────────────┬──────────────┐
   ↓             ↓              ↓
Verified      Rejected       Suspended
   ↓             ↓              ↓
Active       Resubmit       Cannot Sell

A deadline may be associated with a reverification request.

If the seller does not complete the required verification within the allowed period, Woven Stories may restrict or suspend the seller account.


# 7. Vendor Risk

Woven Stories maintains a risk profile for each seller.

Risk is used to determine whether additional monitoring or verification may be required.

Risk does **not** automatically mean that a seller is fraudulent.

Possible risk levels:

* Low
* Medium
* High

## 7.1 Risk Factors

Risk may be affected by signals such as:

### Identity and Business

* Verification problems
* Changes to identity information
* Changes to business information
* Expiring verification documents

### Financial Activity

* Significant changes in sales volume
* Significant changes in payout information
* Unusual refund activity
* Significant payment disputes

### Fulfillment

* High cancellation rate
* High late-shipment rate
* High refund rate
* Significant increase in customer complaints

### Marketplace Reputation

* Significant drop in seller rating
* Repeated customer complaints
* Product authenticity concerns

### Security

* Suspicious account activity
* Important account information changes
* Account recovery events
* Other security-related signals

These signals may increase the seller's risk level and can trigger additional review or reverification.


# 8. Risk-Based Reverification

The seller's risk profile can influence the frequency or type of verification required.

For example, Woven Stories may define hypothetical verification policies such as:

| Risk Level | Example Reverification Interval |
| ---------- | ------------------------------: |
| Low        |                 Every 24 months |
| Medium     |                 Every 12 months |
| High       |                  Every 6 months |

These intervals are business rules for the Woven Stories project and are not intended to represent legal requirements.

Higher-risk situations may also trigger reverification immediately rather than waiting for the next scheduled review.



# 9. Risk Events

Risk changes should be traceable.

Woven Stories records risk events that explain why a seller's risk profile changed.

Examples:

HighRefundRate
PayoutInformationChanged
UnusualSalesIncrease
LateShipmentRateIncreased
VerificationExpired
CustomerComplaint
SuspiciousAccountActivity


Each risk event should contain enough information to answer:

> Why did this seller's risk level change?


# 10. Product Publishing

Seller approval and product approval are separate concepts.

An approved seller can create products, but products may go through a separate moderation process before becoming publicly available.

Example:

Seller Approved
      ↓
Create Product
      ↓
Draft
      ↓
Submitted for Review
      ↓
Moderation
      ↓
Approved
      ↓
Published


This allows Woven Stories to review products independently of the seller's account.


# 11. Initial Business Rules

1. A vendor must select a vendor type during registration.
2. Woven Stories supports Individual Artisans and Businesses.
3. Email and phone verification are required.
4. A vendor must submit a seller application before becoming an approved seller.
5. Only Active sellers can sell products.
6. Seller information requirements depend on the vendor type.
7. An administrator must be able to approve or reject seller applications.
8. A rejected application may be resubmitted.
9. Suspended and blocked sellers cannot sell products.
10. Seller status changes must be traceable.
11. Seller verification is separate from seller status.
12. An Active seller may be required to complete reverification while continuing to sell.
13. Reverification may be triggered by scheduled verification requirements or risk-related events.
14. Risk level does not automatically indicate fraudulent behavior.
15. Risk events should be recorded to explain changes in seller risk.
16. Failure to complete required reverification may result in selling restrictions or suspension.
17. Seller approval and product approval are separate processes.
18. Product moderation may be required before a product becomes publicly available.