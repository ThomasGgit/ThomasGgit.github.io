
---
cabinet: AS01
positioned: Plan 4
systems:

  - name: FJV
    components:
      meter: PV601
      forwardtemp: PV601-GT101
      returntemp: PV601-GT401
  
  - name: VS01
    components:
      meter: PV602
      forwardtemp: GT102
      returntemp: GT402
      pump: CP102
  
  - name: VV01
    components:
      meter: PV603
      forwardtemp: GT103
      returntemp: GT403
      pump: CP103
---
# Undercentral
![](./Example/Fastighet01/Undercentral.svg)
![[Sidintro]]
#system-FJV
![[Framledningsreglering]]
#system-VV01
![[Pumpstart]]
![[Framledningsreglering]]
#system-VS01
![[AI_Controller]]
![[Pumpstart]]
![[Framledningsreglering]]
