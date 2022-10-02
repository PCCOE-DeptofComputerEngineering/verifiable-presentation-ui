## Digital certificate issuance and management software for colleges

##### Project definition
[Link](https://github.com/donew-innovations/moonshot-ideas/issues/3)

##### Context 
[Verifiable Presentations](https://github.com/verifiable-presentation) is an implementation of the [W3C spec](https://www.w3.org/TR/vc-use-cases/) on verifiable credentials and presentations, inspired by the issuance vaccine certificates in India [DIVOC](https://github.com/egovernments/DIVOC). 

##### Project
Extend the [verifiable presentations implementation](https://github.com/verifiable-presentation) and build a UI management layer on top of it that enables any college body to issue digitally verifiable certificates to students. This can start with student body issued certificates and can extend to internal assessment report cards and even degree certificates. 

##### Milestones
- [ ] Set up and run [verifiable presentation back-end implementation](https://github.com/verifiable-presentation/impl) using Docker. Test out the APIs for end to end verifiable presentation creation using HTTPie. If you face any issue or have any questions about this step, open an issue [here](https://github.com/verifiable-presentation/impl/issues/new?assignees=&labels=bug%2Cneeds+triage&template=bug_report.yaml&title=bug%3A+...). 
- [ ] Create basic HTML pages for template creator, credential creator, issuer, holder. Any issues about UI creation, create an issue [here](https://github.com/PCCOE-DeptofComputerEngineering/verifiable-presentation-ui/issues/new). 
- [ ] Figure out where and how you want to deploy the frontend and backend
- [ ] Define detailed use cases to be implemented
- [ ] Implement use cases
- [ ] Create test routines for each use case
- [ ] Get all clubs to adopt this for certificate distribution
