Ideas for QnAMarkup Generator
the script is for a single jurisdiction 

Different scenarios -
* Question with multiple answers:
  - Examples:
    - Grounds
  - A question with multiple answers should have no information in the yes/no section
* Asking one question at a time
  - Examples:
    - Nonpayment
* Element with no children - answer to question provides Explanation and Instructions
  - Examples:
    - LatePayAllowed
    - LateFeeUnreasonable
 * Question where answer depends on some question with multiple answers
   - Examples:
     - LeaseExpiring
     
**Categories for Data Fields for Elements**     
* LegalElements
  - Any children LegalElements that need to be true
* Facts
  - Any facts
  - Facts are often important in elements with no other legal elements
  - Facts could
* LegalCite
  - The information about the applicable law, which is in Finch
* PlainEnglish
  - Plain English d
  - Needed for QnA Markup:
    - Question to see if applicable
    - Neutral Plain English Explanations
    - Information if Yes
    - Information if No
  - Types of Plain English
    - Explainer
    - Instructions
    - Steps
* Remedies
  - The legal remedies if the requirements of this element are met
  - Types of remedies:
    - Actual damages
    - Attorney fees
    - Dismissal of the case
    - Injunction
  - There should be legalcites for these too
* Tools
  - What a party can do if this requirements of this element are met, like file a motion, answer or counterclaim, or make
* Jurisdictions
  - The fields


    
EvictionAction
 * Grounds
   - Nonpayment
     - HousingDefective
     - LatePayAllowed
     - UnreasonableFees
   - LeaseExpiring
     - Lease Expired
       - Term
       - MonthToMonth
       - AtWill
     - Notice
   - BreachLease
     - IllegalActivity
     - DamageToPremises
     - FailureToRepair
     - DifferentLeaseViolation
   - NewLL
 * Notice
   - Challenges to affidavits of service
   - No service
   - Service less than seven (7) days before the initial hearing
   - Service on legal holidays
   - Service by a named plaintiff or agents
   - Substituted service on non
   - Improper substitute service by mail and posting
   - Improper posting on commercial tenant
   - If the defendant is confined to a state institution failure to serve the institution's chief executive officer
   - Improper affidavit of service
   - Untimely or no affidavit of service
   - Waiver of defense
   - Service before filing action
   - Service on business
   - Incomplete service
 * Preconditions
   - The plaintiff is not entitled to possession
   - Plaintiff’s agent is not authorized with a proper power of authority
   - Landlord address disclosure
   - Disclosure of the identity of the principal of the property
   - Trade name registration
   - Foreign corporation
   - Tenant in possession for at least three years
   - Failure to state the facts that authorize recovery of the premises
   - Unauthorized practice of law
   - Failure to attach to the complaint or provide at the initial hearing a copy of the termination notice or lease (Hennepin and Ramsey County Housing Court)
   - Failure to provide defendant with a copy of the lease before commencement of the action
   - Failure to timely file the affidavit of service (Fourth District; Hennepin and Ramsey County Housing Courts)
   - Section 8 Existing Housing Certificate and Voucher Programs: Failure to give notice to the public housing authority
   - Bankruptcy
   - Stay of eviction action pending parallel litigation
   - Failure to join an indispensable party
   - Lack of jurisdiction over Indian trust property
   - Action is inappropriate method to resolve complex claims
   - Failure to sign complaint
   - Landlord's preparation of summons
   - Premature action or claim that had not accrued
   - Plaintiff's voluntary dismissal
   - Lease Signed under Duress
   - Filing case in violation of consumer fraud order
   - Domestic abuse
   - Summons content
   - Failure to use written lease
   - Mootness
   - Plaintiff’s default
   - Statute of frauds
   - Tenant waiver of claims
   - Statute of limitations
   - Servicemembers Civil Relief Act
   - Accord and satisfaction
   - Lack of subject matter jurisdiction
 * OtherDefenses
   - Discrimination
   - Retaliation
