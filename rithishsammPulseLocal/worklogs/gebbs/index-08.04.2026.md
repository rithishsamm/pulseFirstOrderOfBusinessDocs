**Task**: Create an Architectural diagram for gebbs

**Domain Endpoints (Route53):**
1) https://newgebbs.pulsework360.com/ - 15.207.183.126 (EndPoint: EC2: Newgebbs-New)
2) https://ap2.pulsework360.com/ - 13.127.125.78 (EndPoint: EC2)
3) https://connecthub.pulsework360.com/login -    -> (LB) k8s-connecth-connecth-d51e9df37a-1965228776.ap-south-1.elb.amazonaws.com(Route)

**EC2 Instances:**
1) Newgebbs-New - 15.207.183.126 
2) Ap2-ast-New-gebbs - 13.127.125.78
3) k8s-connecth-connecth-d51e9df37a-1965228776.ap-south-1.elb.amazonaws.com(Route)

**Example(previous diagram):**

![[AWS Architecture.pdf]]


**Tailored Final Diagram:**
![[gebbsinfra-archDiagram.pdf]]