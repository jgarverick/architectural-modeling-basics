---
marp: true
theme: midnight
transition: fade

style: |
  .columns {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
  }
  .columns3 {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 1rem;
  } 
  img[alt~="center"] {
    display: block;
    margin: 0 auto;
  }
  
  @import 'https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css'
---
<!-- _class: "title-slide" -->
# Architecture Modeling Basics
![bg right](https://upload.wikimedia.org/wikipedia/commons/a/a1/TOGAF_ADM.jpg)

---

## Agenda

- Modeling frameworks
- Heavy or light?
- Pros and cons
- Relevant links

---

## Modeling Frameworks

- Several frameworks to choose from
  - ArchiMate modeling language
  - The Open Group Architectural Framework (TOGAF)
  - Zachmann Framework
- TOGAF was born in the 1990s as a derivative of the Department of Defense's Technical Architecture Framework for Information Management (TAFIM) as well as the Integrated Architecture Framework (IAF) from Capgemini  
- ArchiMate is based on the IEEE 1471 standard for describing "software-intensive systems"

---

## Heavy or Light?

> Modeling frameworks can generally be viewed as heavy, since they are prescriptive in how terms are used, interactions are defined, and layers are composed.

> Using the methodologies for classifying different segments of a solution or visualizing those segments will yield a more well-rounded solution, regardless of adherence to the meteamodel or strict interaction rules.

---

## Is it worth the overhead?

<div class="columns">
<div>

### Pros

- Structured categories for components
- Ubiquitous taxonomy
- Well-defined components and interactions
- Views and viewpoints provide insight into potential changes
- Dependency mapping at several levels

</div>
<div>

### Cons

- Lots of process
- Lots of academic material
- Structure can be rigid
- Models require consistent maintenance
- Abstract concepts may be difficult to capture

</div>
</div>

---

## Related Links

ArchiMate: https://www.opengroup.org/archimate-forum/archimate-overview 
TOGAF: https://www.opengroup.org/togaf

