<p align="center"> 
    <img src="https://regov-store.s3.ap-southeast-1.amazonaws.com/REGOV+Logo_CMYK.png" width="200" >
</p>

# Welcome to our PopQuiz!

#### Attempt 3 questions from the following; however, questions 3 & 4 are mandatory.
### Question 1 (Algorithm and Data Structure)
*Attempt all three questions in this section*
#### 1. Given the head of a linked list, return the list after sorting it in ascending order.###

<p align="Left"> 
    <img src="https://regov-store.s3.ap-southeast-1.amazonaws.com/link-list.png" width="500" >
</p>

e.g:

`Input: head = [4,2,1,3]`
`Output: [1,2,3,4]`

`Input: head = [-1,5,3,4,0]`
`Output: [-1,0,3,4,5]`

**Constraints:**

- The number of nodes in the list is in the range [0, 5 * 10 <sup>4 </sup>].

-  -10 <sup>5</sup> <= Node.val <= 10 <sup>5</sup> 


**Follow up:** Can you sort the linked list in `O(n logn)` time and `O(1)` memory (i.e. constant space)?

#### 2. You are given an array of strings tokens that represents an arithmetic expression in a Reverse Polish Notation. Evaluate the expression. Return an integer that represents the value of the expression.

**Note that:**

- The valid operators are '+', '-', '*', and '/'.
- Each operand may be an integer or another expression.
- The division between two integers always truncates toward zero.
- There will not be any division by zero.
- The input represents a valid arithmetic expression in a reverse polish notation.
- The answer and all the intermediate calculations can be represented in a 32-bit integer.

e.g 1:

`Input: tokens = ["4","2","+","5","*"]`
`Output: 30`
`Explanation: ((4 + 2) * 5) = 30`

e.g 2:

`Input: tokens = ["4","13","5","/","+"]`
`Output: 6`
`Explanation: (4 + (13 / 5)) = 6`


**Constraints:**

`1 <= tokens.length <= 104`
`tokens[i] is either an operator: "+", "-", "*", or "/", or an integer in the range [-200, 200].`


#### 3. Maximum Product Subarray

Given an integer array nums, find a subarray that has the largest product, and return the product.

The test cases are generated so that the answer will fit in a 32-bit integer.

e.g 1:

`Input: nums = [2,3,-2,4]`
`Output: 6`
`Explanation: [2,3] has the largest product 6.`

e.g 1:

`Input: nums = [-2,0,-1]`
`Output: 0`
`Explanation: The result cannot be 2, because [-2,-1] is not a subarray.`

**Constraints:**

- `1 <= nums.length <= 2 * 104`
- `-10 <= nums[i] <= 10`
- `The product of any prefix or suffix of nums is guaranteed to fit in a 32-bit integer.`


### Question 2 (Customer Onboarding & Asset Management App)

Create an API solution for a Unit Trust company called MTCT. MTCT consists of an headquarter (HQ), Two branches, multiple financial advisers (Agent), and over 100,000 investors. The HQ and its branches maintain daily operations of the business processes, and the HQ reconcile the daily onboarding of new customers, sales transactions, and KYC in the respective branches. The HQ is solely responsible to update new financial asset products that will reflect across the branch units.
The system should include a customer portal (Investor Portal) for self-service to buy and sell assets.

<p> Expectations: </p>

- Implement a simple solution that captures the basic functionalties of the actors, processes, and with customer portal to effect the onboarding process
- Implement any process you're familiar with in the Financial industry

## Mandatory
### Question 3 (Web3 Identity Solution)

<p> Develop a basic Web3 Identity solution called WeIDY. The WeIDY is intended to demonstrated workflow of Verifiable Credentials and its inhernet workflows on a basic level.<p/>

<p> WeIDY should have seven key capabilities: </p>

- Agents is able to connect to local or remote (Sandbox e.g Green-light) Indy pool. Note: Use any Indy DLT Ledger of your choice
- Connection between two or more agents
- Agents can performing simple workflow: (1) Issuers issues credentials (2) Holders accepts and stores the credentials (3) Verifiers, verifies Credentials
- Credentials requests and presentation
- List credentials existing in a wallet
- User registration
- Login & Logout

<p> Expectations: </p>

- WeIDY is an API based application. 
- WeIDY is a dockerized
- Dockerize a local Indy network / Connect to any available test network
- WeIDY has clear instruction in the README on how to run the app locally
- WeIDY APIs should have clearly written comments on the code implementation
- WeIDY should expose APIs on Swagger
- The implementation should be simple and straight to the point

<p> Reference code repositories by Hyperledger Aries and W3C guidelines  </p>

 - [Hyperledger Aries] (https://github.com/hyperledger/aries-framework-javascript)
 - [Aries Documentation] (https://aries.js.org/)
 - [W3C VC Credentials] (https://www.w3.org/TR/vc-data-model/)
 - [W3C DID] (https://www.w3.org/TR/did-core/)



## Mandatory
### Question 4 (System Design & Solution Architecture)

Create system design architecture of integration between applications in Question 2 and 3. 

The next version of the section 2 application intends to have Web3 Self-sovereign identity for customer onboarding, verifiable credentials for asset management, and offboarding process. This version extends to support portability on both on-premise and cloud-native deployment but is geared more towards cloud workload. It will use a Verifiable Credential Self-sovereign identity management paradigm, particularly open-source libraries such as Aries, Indy, etc. The architecture must capture the core principles of a well-architectured design supporting maintainability, scalability, and reliability. The key highlight of this system design is the integration with Web3 SSI module. The system design will integrate with Web3 Verifiable Credentials called WeIDY. WeIDY will handle the onboarding and user management credentialing for the Unit Trust company MTCT.

<p> Expectations & Success Criteria: </p>

- Create system architecture design
- Create a Data Flow Diagram (DFD) digrams
- The architecture should cover Web3, micro-services / modules backend layer, and actors & interfaces
- Label all services and components and its rationale
- The system design should adopt modern technologies and best practices
- Document in a Wiki description of the architecture deisgn
- Feel free to design however you feel professionally inclined to do. Implementations are all yours.

 ## Notes
  - Use Node.js (Typescript preferrably) or Python
  - Create a README.MD document with instructions
  - Include well organized and explanatory commnets
  - Produce concise/short technical design documentation
  - Upload your code in either Github, Gitlab or any version control.
  - If you have any questions, do reach out to the emails below

## Submission process

1. Email your complete work to techchallenge@regovtech.com & paul.agada@regovtech.com
2. Submit Github Repo

Good Luck!