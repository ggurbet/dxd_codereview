Grant Proposal | [751 - CA - NiftyRow NFT & Security Tokens Marketplace Autosave Autosave](https://portal.devxdao.com/public-proposals/751)
------------ | -------------
Milestone | 1
Milestone Titles | Nifty Row NFT Auction Marketplace in Rust for Casper blockchain - Submission 1
OP | Nifty Row
Reviewer | Gökhan Gurbetoğlu <crdao@ggurbet.com>

# Milestone Details

## Details & Acceptance Criteria

**Details of what will be delivered in milestone:**

App launch of Nifty Row for Desktop (browser) with CASPER NFTs support:
1. Implement minting, auction bids and buy now features based on CASPER smart contracts i.e. the Casper NFT Standard CEP-47 or CEP-78 .
2. Desktop Browser based Marketplace integration with at least 1 Casper Web3.0 wallet (e.g. Casper Signer)
3. Deploy and Conduct Testing on CASPER testnet
4. Launch Nifty Row on CASPER Mainnet

**Acceptance criteria:**

Nifty Row users will be able to perform minting, auction bids and outright buys with Casper Tokens via a desktop internet browser whereby the assets are represented by Casper NFT (CEP47 or CEP 78).

**Additional notes regarding submission from OP:**

Nifty Row Casper Blockchain integration milestone 1 allows users to participate in an NFT auction. Using the Casper-Wallet, NFT Creators can mint a CEP47NFT while specifying an time period for the auction. Buyers/collectors can bid for the NFT the highest bidder wins the auction.

## Milestone Submission

The following milestone assets/artifacts were submitted for review:

Repository | Revision Reviewed
------------ | -------------
https://github.com/Nifty-Row/casper-frontend | 6329982


# Install & Usage Testing Procedure and Findings

_Provide a detailed review of your install and usage testing of the project. Highlight any issues setting up the project,
including shortcomings in the documentation/setup instructions. Test the usage of the project against the Acceptance Criteria
provided for the grant milestone._

## Overall Impression of usage testing

_Summarize your impression following detailed usage testing and provide a `PASS`, `FAIL`, or `PASS With Notes` for the requirements
below. In the case of `PASS With Notes`, make sure that the notes for improvement are clearly spelled out in this section._

Requirement | Finding
------------ | -------------
Project builds without errors | PASS / FAIL / PASS with Notes
Documentation provides sufficient installation/execution instructions | PASS / FAIL / PASS with Notes
Project functionality meets/exceeds acceptance criteria and operates without error | PASS / FAIL / PASS with Notes

# Unit / Automated Testing

_Summarize the result of the unit testing / automated testing / integration testing provided in the Milestone. Feel free to include
automated test output, either as text, image or other artifact. Provide a `PASS`, `FAIL`, or `PASS With Notes` for the requirements
below. In the case of `PASS With Notes`, make sure that the notes for improvement are clearly spelled out in this section._

Requirement | Finding
------------ | -------------
Unit Tests - At least one positive path test | PASS / FAIL / PASS with Notes
Unit Tests - At least one negative path test | PASS / FAIL / PASS with Notes
Unit Tests - Additional path tests | PASS / FAIL / PASS with Notes

# Documentation

### Code Documentation

Code documentation is almost inexistant. There is only a few comments in the source. Also, there are many commented out code that should have been removed for the development branch. Code documentation should be improved in the next milestone.

Requirement | Finding
------------ | -------------
Code Documented | PASS with Notes

### Project Documentation

_Summarize the project level documentation you encountered. This covers the information provided in the README for the project, 
as well any exampled provided. Provide a `PASS`, `FAIL`, or `PASS With Notes` for the requirements
below. In the case of `PASS With Notes`, make sure that the notes for improvement are clearly spelled out in this section._

Requirement | Finding
------------ | -------------
Usage Documented | PASS / FAIL / PASS with Notes
Example Documented | PASS / FAIL / PASS with Notes

## Overall Conclusion on Documentation

_Summarize your review of the documentation in this project, including code, usage and examples_

# Open Source Practices

## Licenses

The project is licensed under MIT License.

Requirement | Finding
------------ | -------------
OSI-approved open source software license | PASS

## Contribution Policies

The project contains a detailed CONTRIBUTING policy that links to a Code of Conduct policy, however the link is dead and the file is not present. Also, SECURITY policy does not have its own file and it is not clearly mentioned in the CONTRIBUTING policy file. These need to be added and updated. Pull requests and Issues on the repository are enabled.

Requirement | Finding
------------ | -------------
OSS contribution best practices | PASS with Notes

# Coding Standards

## General Observations

Source code is well-written and thought out. It is easily readable. General best coding practices are used throughout the project. Overall sufficient work is done.

There are some commented out code that is still present in the source, which as a suggestion, should be removed from production branch in the future updates.


# Final Conclusion

_Summarize your final conclusion, and provide your motivation for your recommendation below. For example, you may say 'Reviewer recommends that this
submission should fail code review, because it does not contain an OSI-approved open source license'_

# Recommendation

Recommendation | PASS / FAIL / PASS with Notes
------------ | -------------
