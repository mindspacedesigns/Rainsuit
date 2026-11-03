# FAQs and FAQPage Schema: Informational Version

Site: https://www.kainternational.co.in

This file replaces the earlier brand and promotional FAQs with informational, search-driven FAQs. Each page has two parts:

1. On-page FAQs (Q&A to show on the page).
2. FAQPage JSON-LD, built from exactly the same questions and answers.

## How these FAQs were written

- Questions follow what people commonly search for on each topic, for example how often to change cubicle curtains, how to size an air curtain, which PVC strip thickness to choose, how to mount an IV hanger, and how to measure for blinds.
- No company name, no claims such as best, leading or world-class, and no call-to-action. Every answer is general product knowledge that helps the reader decide or prepare.
- Question text and answer text are identical in the on-page list and in the schema, which is what Google expects for FAQPage markup.
- Numbers (thickness, overlap, intervals) are stated as general guidance with words like "about" and "commonly", because exact values vary by facility policy and product.

## Contents

| # | Page | URL | FAQs |
|---|------|-----|:----:|
| 1 | Home | `/` | 6 |
| 2 | Hospital Curtains | `/hospital-curtain.html` | 6 |
| 3 | Hospital Cubicle Tracks | `/hospital-cubicle-tracks.html` | 6 |
| 4 | Air Curtains | `/air-curtains.html` | 6 |
| 5 | PVC Curtains | `/pvc-curtains.html` | 6 |
| 6 | IV Hangers | `/iv-hangers.html` | 6 |
| 7 | Roller Blinds | `/blends.htm` | 6 |
| 8 | Aluminium Partitions | `/aluminium-partition.html` | 6 |
| 9 | Monitor Stand | `/monitor-stand.html` | 6 |
| 10 | Furnishing | `/furnishing.html` | 5 |
| 11 | Hospital Furniture | `/hospital-furniture.html` | 5 |
| 12 | Enquiry | `/enquiry.html` | 6 |
| 13 | About Us | `/about-us.html` | 5 |
| 14 | Products | `/products.html` | 6 |
| 15 | Contact | `/contact.html` | 5 |

---

## 1. Home

URL: https://www.kainternational.co.in/

### On-page FAQs

Q1: What equipment is commonly used to create privacy in a multi-bed hospital ward?  
A: Ceiling-mounted cubicle tracks with privacy curtains are the most common method, because they can be opened or closed as needed. Where fixed separation is required, such as for consultation cabins, procedure rooms or administrative areas, partition systems made of aluminium frames with glass or board panels are used.

Q2: What is the difference between a hospital curtain and a normal home curtain?  
A: Hospital curtains are made from fabrics intended for frequent washing and are usually flame-retardant, and they often have a mesh panel at the top for air and light flow. Home curtains are mainly decorative and are not designed for repeated laundering under infection-control routines.

Q3: What is a hospital cubicle track and why is it fixed to the ceiling?  
A: A cubicle track is a lightweight rail, usually made of aluminium, that holds curtain carriers so the curtain slides smoothly around a bed. It is fixed to or suspended from the ceiling so that the floor stays clear for beds, trolleys and equipment.

Q4: What is the difference between an IV hanger and an IV pole?  
A: An IV hanger is an overhead fitting with hooks for infusion bags, mounted on the ceiling or on a track. An IV pole is a free-standing, wheeled stand that stands on the floor. Overhead hangers keep the floor area free, while poles can be moved anywhere in the room.

Q5: Which products help control dust and insects at hospital entrances?  
A: Air curtains and PVC strip curtains are the two common options. An air curtain blows a fast stream of air across the opening, while a PVC strip curtain is a physical barrier made of overlapping flexible strips. Neither replaces proper door and ventilation design.

Q6: What should be checked before choosing ward curtains, tracks or partitions?  
A: Check the room dimensions, ceiling height and ceiling type, the fabric or material requirements for fire safety and washing, the expected traffic and cleaning method, and any fire-safety or accreditation requirements of the facility. Taking accurate measurements first avoids costly changes later.

### FAQPage schema

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "@id": "https://www.kainternational.co.in/#faq",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What equipment is commonly used to create privacy in a multi-bed hospital ward?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Ceiling-mounted cubicle tracks with privacy curtains are the most common method, because they can be opened or closed as needed. Where fixed separation is required, such as for consultation cabins, procedure rooms or administrative areas, partition systems made of aluminium frames with glass or board panels are used."
      }
    },
    {
      "@type": "Question",
      "name": "What is the difference between a hospital curtain and a normal home curtain?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Hospital curtains are made from fabrics intended for frequent washing and are usually flame-retardant, and they often have a mesh panel at the top for air and light flow. Home curtains are mainly decorative and are not designed for repeated laundering under infection-control routines."
      }
    },
    {
      "@type": "Question",
      "name": "What is a hospital cubicle track and why is it fixed to the ceiling?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "A cubicle track is a lightweight rail, usually made of aluminium, that holds curtain carriers so the curtain slides smoothly around a bed. It is fixed to or suspended from the ceiling so that the floor stays clear for beds, trolleys and equipment."
      }
    },
    {
      "@type": "Question",
      "name": "What is the difference between an IV hanger and an IV pole?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "An IV hanger is an overhead fitting with hooks for infusion bags, mounted on the ceiling or on a track. An IV pole is a free-standing, wheeled stand that stands on the floor. Overhead hangers keep the floor area free, while poles can be moved anywhere in the room."
      }
    },
    {
      "@type": "Question",
      "name": "Which products help control dust and insects at hospital entrances?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Air curtains and PVC strip curtains are the two common options. An air curtain blows a fast stream of air across the opening, while a PVC strip curtain is a physical barrier made of overlapping flexible strips. Neither replaces proper door and ventilation design."
      }
    },
    {
      "@type": "Question",
      "name": "What should be checked before choosing ward curtains, tracks or partitions?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Check the room dimensions, ceiling height and ceiling type, the fabric or material requirements for fire safety and washing, the expected traffic and cleaning method, and any fire-safety or accreditation requirements of the facility. Taking accurate measurements first avoids costly changes later."
      }
    }
  ]
}
</script>
```

---

## 2. Hospital Curtains

URL: https://www.kainternational.co.in/hospital-curtain.html

### On-page FAQs

Q1: What are hospital curtains used for?  
A: Hospital curtains, also called cubicle or privacy curtains, divide a bed or treatment space from the rest of the room to give patients privacy. They are used in wards, ICUs, emergency areas, dialysis units, examination rooms and clinics.

Q2: How often should hospital curtains be washed or changed?  
A: There is no single universal rule, so the facility's infection-control policy decides. Common practice is to change curtains when they are visibly soiled, after a patient on isolation precautions is discharged, and at routine intervals such as every one to three months or quarterly, depending on the risk level of the area.

Q3: What fabric is best for hospital curtains?  
A: Polyester and polyester-blend fabrics are widely used because they are durable, wash well and can be made flame-retardant. Inherently flame-retardant yarns keep their protection after repeated washing, while chemically treated fabrics may lose protection over time, so the fabric's test or certification details should be checked.

Q4: How do I decide the size of a hospital curtain?  
A: Measure the length of the track run and the drop from the track to the floor. The finished curtain is made wider than the track so that it hangs in folds, and it usually stops a short distance above the floor to ease cleaning and airflow. The exact fullness and floor gap should be confirmed before ordering.

Q5: Why do hospital curtains have a mesh panel at the top?  
A: The mesh or net panel allows air, light and, where fitted, fire-sprinkler water to pass through, while the solid fabric below gives privacy. It also lets staff see the general condition of the space above the curtain line.

Q6: Are disposable curtains better than reusable curtains?  
A: Disposable curtains are replaced instead of laundered, so they are often chosen for isolation rooms or high-risk areas. Reusable curtains are washed and rehung, which can cost less over time but needs a laundering and tracking routine. The right choice depends on the area, budget and infection-control policy.

### FAQPage schema

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "@id": "https://www.kainternational.co.in/hospital-curtain.html#faq",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What are hospital curtains used for?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Hospital curtains, also called cubicle or privacy curtains, divide a bed or treatment space from the rest of the room to give patients privacy. They are used in wards, ICUs, emergency areas, dialysis units, examination rooms and clinics."
      }
    },
    {
      "@type": "Question",
      "name": "How often should hospital curtains be washed or changed?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "There is no single universal rule, so the facility's infection-control policy decides. Common practice is to change curtains when they are visibly soiled, after a patient on isolation precautions is discharged, and at routine intervals such as every one to three months or quarterly, depending on the risk level of the area."
      }
    },
    {
      "@type": "Question",
      "name": "What fabric is best for hospital curtains?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Polyester and polyester-blend fabrics are widely used because they are durable, wash well and can be made flame-retardant. Inherently flame-retardant yarns keep their protection after repeated washing, while chemically treated fabrics may lose protection over time, so the fabric's test or certification details should be checked."
      }
    },
    {
      "@type": "Question",
      "name": "How do I decide the size of a hospital curtain?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Measure the length of the track run and the drop from the track to the floor. The finished curtain is made wider than the track so that it hangs in folds, and it usually stops a short distance above the floor to ease cleaning and airflow. The exact fullness and floor gap should be confirmed before ordering."
      }
    },
    {
      "@type": "Question",
      "name": "Why do hospital curtains have a mesh panel at the top?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The mesh or net panel allows air, light and, where fitted, fire-sprinkler water to pass through, while the solid fabric below gives privacy. It also lets staff see the general condition of the space above the curtain line."
      }
    },
    {
      "@type": "Question",
      "name": "Are disposable curtains better than reusable curtains?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Disposable curtains are replaced instead of laundered, so they are often chosen for isolation rooms or high-risk areas. Reusable curtains are washed and rehung, which can cost less over time but needs a laundering and tracking routine. The right choice depends on the area, budget and infection-control policy."
      }
    }
  ]
}
</script>
```

---

## 3. Hospital Cubicle Tracks

URL: https://www.kainternational.co.in/hospital-cubicle-tracks.html

### On-page FAQs

Q1: What is a hospital cubicle track?  
A: A hospital cubicle track is a rail fixed to the ceiling that carries curtain hooks or carriers, allowing a privacy curtain to glide smoothly around a bed. It can be straight, L-shaped or U-shaped to match the bed layout.

Q2: What is the difference between surface-mounted and suspended cubicle tracks?  
A: A surface-mounted track is fixed directly to the ceiling, while a suspended track hangs from rods or hangers. Suspended mounting is used when the ceiling is high or cannot take a direct fixing; some specifications recommend hangers when ceilings are higher than about 2.7 metres, to keep curtain length practical.

Q3: What material is used for cubicle tracks?  
A: Extruded aluminium is the most common material because it is light, resists rust and can be bent into curves. It is usually finished in white powder coating or silver anodising.

Q4: Can a cubicle track be curved, and how tight can the bend be?  
A: Yes, aluminium tracks can be bent to form corners and U-shapes. Some specifications ask for a minimum bend radius of around 450 mm, because tighter bends can make carriers stick, so the manufacturer's limit should be followed.

Q5: How is a cubicle track fixed to a false ceiling?  
A: A track is not normally loaded onto the false-ceiling tile. It is fixed to the structural slab with suspension rods, or clipped to the ceiling grid where the grid is rated for the load. The fixing method should be checked with the ceiling installer.

Q6: What accessories are needed with a cubicle track?  
A: A track system usually needs curtain carriers or hooks, end stops, joiners for long runs, and bends for corners. A curtain removal point or gate makes taking down the curtain for washing easier.

### FAQPage schema

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "@id": "https://www.kainternational.co.in/hospital-cubicle-tracks.html#faq",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What is a hospital cubicle track?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "A hospital cubicle track is a rail fixed to the ceiling that carries curtain hooks or carriers, allowing a privacy curtain to glide smoothly around a bed. It can be straight, L-shaped or U-shaped to match the bed layout."
      }
    },
    {
      "@type": "Question",
      "name": "What is the difference between surface-mounted and suspended cubicle tracks?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "A surface-mounted track is fixed directly to the ceiling, while a suspended track hangs from rods or hangers. Suspended mounting is used when the ceiling is high or cannot take a direct fixing; some specifications recommend hangers when ceilings are higher than about 2.7 metres, to keep curtain length practical."
      }
    },
    {
      "@type": "Question",
      "name": "What material is used for cubicle tracks?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Extruded aluminium is the most common material because it is light, resists rust and can be bent into curves. It is usually finished in white powder coating or silver anodising."
      }
    },
    {
      "@type": "Question",
      "name": "Can a cubicle track be curved, and how tight can the bend be?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes, aluminium tracks can be bent to form corners and U-shapes. Some specifications ask for a minimum bend radius of around 450 mm, because tighter bends can make carriers stick, so the manufacturer's limit should be followed."
      }
    },
    {
      "@type": "Question",
      "name": "How is a cubicle track fixed to a false ceiling?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "A track is not normally loaded onto the false-ceiling tile. It is fixed to the structural slab with suspension rods, or clipped to the ceiling grid where the grid is rated for the load. The fixing method should be checked with the ceiling installer."
      }
    },
    {
      "@type": "Question",
      "name": "What accessories are needed with a cubicle track?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "A track system usually needs curtain carriers or hooks, end stops, joiners for long runs, and bends for corners. A curtain removal point or gate makes taking down the curtain for washing easier."
      }
    }
  ]
}
</script>
```

---

## 4. Air Curtains

URL: https://www.kainternational.co.in/air-curtains.html

### On-page FAQs

Q1: How does an air curtain work?  
A: An air curtain is a fan unit mounted above an opening that blows a fast, narrow stream of air downward across the doorway. This moving air forms an invisible barrier that reduces the exchange of air, dust and insects between the two sides of the opening.

Q2: How do I choose the right size of air curtain?  
A: The unit should be at least as wide as the opening, and wide openings can be covered with two or more units placed end to end. The air stream must also reach the floor with enough speed, so the door height must fall within the unit's rated mounting height.

Q3: Can an air curtain replace a door?  
A: No. An air curtain reduces air exchange across an open doorway but does not stop people, wind or pressure differences in the way a closed door does. It works best as an addition to a door or opening that is frequently used.

Q4: Where should an air curtain be installed?  
A: It is usually mounted horizontally above the door on the inside, with a clear path for the air to travel from top to floor. Obstructions such as signs, lights or door hardware in the air path reduce performance.

Q5: Should I choose a heated or unheated air curtain?  
A: Unheated (ambient) units are used to keep out insects and dust in most warm-climate buildings. Heated units are used mainly where a significant temperature difference has to be managed, such as in cold climates.

Q6: Do air curtains stop flying insects?  
A: They can greatly reduce the number of flying insects entering an opening when the unit covers the full width and the air reaches the floor. They are not a complete barrier, so they are usually combined with other measures.

### FAQPage schema

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "@id": "https://www.kainternational.co.in/air-curtains.html#faq",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "How does an air curtain work?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "An air curtain is a fan unit mounted above an opening that blows a fast, narrow stream of air downward across the doorway. This moving air forms an invisible barrier that reduces the exchange of air, dust and insects between the two sides of the opening."
      }
    },
    {
      "@type": "Question",
      "name": "How do I choose the right size of air curtain?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The unit should be at least as wide as the opening, and wide openings can be covered with two or more units placed end to end. The air stream must also reach the floor with enough speed, so the door height must fall within the unit's rated mounting height."
      }
    },
    {
      "@type": "Question",
      "name": "Can an air curtain replace a door?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "No. An air curtain reduces air exchange across an open doorway but does not stop people, wind or pressure differences in the way a closed door does. It works best as an addition to a door or opening that is frequently used."
      }
    },
    {
      "@type": "Question",
      "name": "Where should an air curtain be installed?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "It is usually mounted horizontally above the door on the inside, with a clear path for the air to travel from top to floor. Obstructions such as signs, lights or door hardware in the air path reduce performance."
      }
    },
    {
      "@type": "Question",
      "name": "Should I choose a heated or unheated air curtain?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Unheated (ambient) units are used to keep out insects and dust in most warm-climate buildings. Heated units are used mainly where a significant temperature difference has to be managed, such as in cold climates."
      }
    },
    {
      "@type": "Question",
      "name": "Do air curtains stop flying insects?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "They can greatly reduce the number of flying insects entering an opening when the unit covers the full width and the air reaches the floor. They are not a complete barrier, so they are usually combined with other measures."
      }
    }
  ]
}
</script>
```

---

## 5. PVC Curtains

URL: https://www.kainternational.co.in/pvc-curtains.html

### On-page FAQs

Q1: What thickness of PVC strip curtain should I choose?  
A: As a general guide, about 2 mm is used for personnel doors at normal temperature, about 3 mm for cold rooms and mixed traffic, and about 4 mm for heavy traffic such as forklifts. Thicker strips hang flatter but need more force to push through.

Q2: How much should PVC strips overlap?  
A: Strips normally overlap by about 30 to 50 percent. A 50 percent overlap is commonly used for cold rooms and areas where temperature control matters, while a lower overlap lets people and trolleys pass more easily.

Q3: How do I measure a doorway for a PVC strip curtain?  
A: Measure the clear width of the opening and the height from the mounting point to the floor. Because of the overlap, the total strip width ordered is usually 30 to 50 percent more than the opening width, and the strips should stop just above the floor.

Q4: What is the difference between standard and polar-grade PVC?  
A: Standard PVC becomes stiff and can crack at very low temperatures. Polar or freezer-grade PVC stays flexible in cold conditions and is the type normally specified for cold rooms and freezers.

Q5: How long do PVC strip curtains last?  
A: Life depends on traffic and environment. Supplier guidance suggests about 4 to 6 years for light pedestrian use and 1 to 2 years where forklifts hit the strips regularly, with cold-room use falling in between.

Q6: How should PVC strip curtains be cleaned?  
A: Wipe the strips with warm water and a mild detergent using a soft cloth, then rinse and let them dry. Strong solvents should be avoided because they can cloud or damage the PVC.

### FAQPage schema

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "@id": "https://www.kainternational.co.in/pvc-curtains.html#faq",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What thickness of PVC strip curtain should I choose?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "As a general guide, about 2 mm is used for personnel doors at normal temperature, about 3 mm for cold rooms and mixed traffic, and about 4 mm for heavy traffic such as forklifts. Thicker strips hang flatter but need more force to push through."
      }
    },
    {
      "@type": "Question",
      "name": "How much should PVC strips overlap?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Strips normally overlap by about 30 to 50 percent. A 50 percent overlap is commonly used for cold rooms and areas where temperature control matters, while a lower overlap lets people and trolleys pass more easily."
      }
    },
    {
      "@type": "Question",
      "name": "How do I measure a doorway for a PVC strip curtain?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Measure the clear width of the opening and the height from the mounting point to the floor. Because of the overlap, the total strip width ordered is usually 30 to 50 percent more than the opening width, and the strips should stop just above the floor."
      }
    },
    {
      "@type": "Question",
      "name": "What is the difference between standard and polar-grade PVC?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Standard PVC becomes stiff and can crack at very low temperatures. Polar or freezer-grade PVC stays flexible in cold conditions and is the type normally specified for cold rooms and freezers."
      }
    },
    {
      "@type": "Question",
      "name": "How long do PVC strip curtains last?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Life depends on traffic and environment. Supplier guidance suggests about 4 to 6 years for light pedestrian use and 1 to 2 years where forklifts hit the strips regularly, with cold-room use falling in between."
      }
    },
    {
      "@type": "Question",
      "name": "How should PVC strip curtains be cleaned?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Wipe the strips with warm water and a mild detergent using a soft cloth, then rinse and let them dry. Strong solvents should be avoided because they can cloud or damage the PVC."
      }
    }
  ]
}
</script>
```

---

## 6. IV Hangers

URL: https://www.kainternational.co.in/iv-hangers.html

### On-page FAQs

Q1: What is an IV hanger?  
A: An IV hanger is an overhead fitting with hooks for holding infusion bags and, in some designs, other lightweight equipment above a patient bed. It can be fixed to the ceiling or slide along a ceiling track.

Q2: What is the difference between a ceiling IV hanger and a floor IV pole?  
A: A ceiling IV hanger stays out of the way and frees floor space around the bed, but it can be used only in the area it covers. A floor IV pole is wheeled and can travel with the patient, but it takes floor space and can tip if overloaded.

Q3: What types of IV hangers are available?  
A: The common types are fixed ceiling-mounted hangers, track-mounted hangers that glide on a cubicle or IV track, and telescopic hangers that adjust in height. The number of hooks usually ranges from two to five.

Q4: Which material is better for IV hangers, aluminium or stainless steel?  
A: Aluminium is light and corrosion-resistant, which suits track-mounted designs. Stainless steel is stronger and resists corrosion and frequent disinfection but is heavier. The choice depends on load, mounting method and cleaning routine.

Q5: How is an IV hanger installed safely?  
A: The hanger must be fixed to a structural part of the ceiling, not to a false-ceiling tile, using fixings suited to the load. Always check the rated weight of the hanger against the bags or devices that will be hung from it.

Q6: Can an IV hanger be used along with a cubicle curtain track?  
A: Yes. A dedicated IV track or IV carrier can run alongside or inside the curtain track, so infusion bags can move with the patient bed. Carriers with locking wheels help the load run smoothly through bends.

### FAQPage schema

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "@id": "https://www.kainternational.co.in/iv-hangers.html#faq",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What is an IV hanger?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "An IV hanger is an overhead fitting with hooks for holding infusion bags and, in some designs, other lightweight equipment above a patient bed. It can be fixed to the ceiling or slide along a ceiling track."
      }
    },
    {
      "@type": "Question",
      "name": "What is the difference between a ceiling IV hanger and a floor IV pole?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "A ceiling IV hanger stays out of the way and frees floor space around the bed, but it can be used only in the area it covers. A floor IV pole is wheeled and can travel with the patient, but it takes floor space and can tip if overloaded."
      }
    },
    {
      "@type": "Question",
      "name": "What types of IV hangers are available?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The common types are fixed ceiling-mounted hangers, track-mounted hangers that glide on a cubicle or IV track, and telescopic hangers that adjust in height. The number of hooks usually ranges from two to five."
      }
    },
    {
      "@type": "Question",
      "name": "Which material is better for IV hangers, aluminium or stainless steel?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Aluminium is light and corrosion-resistant, which suits track-mounted designs. Stainless steel is stronger and resists corrosion and frequent disinfection but is heavier. The choice depends on load, mounting method and cleaning routine."
      }
    },
    {
      "@type": "Question",
      "name": "How is an IV hanger installed safely?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The hanger must be fixed to a structural part of the ceiling, not to a false-ceiling tile, using fixings suited to the load. Always check the rated weight of the hanger against the bags or devices that will be hung from it."
      }
    },
    {
      "@type": "Question",
      "name": "Can an IV hanger be used along with a cubicle curtain track?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes. A dedicated IV track or IV carrier can run alongside or inside the curtain track, so infusion bags can move with the patient bed. Carriers with locking wheels help the load run smoothly through bends."
      }
    }
  ]
}
</script>
```

---

## 7. Roller Blinds

URL: https://www.kainternational.co.in/blends.htm

### On-page FAQs

Q1: What is a roller blind and how does it work?  
A: A roller blind is a single sheet of fabric wound around a tube at the top of a window. It is raised or lowered with a chain, cord or spring mechanism, and sits flat against the window when lowered.

Q2: What is the difference between sheer, light-filtering and blackout roller blinds?  
A: Sheer or sunscreen fabrics reduce glare while keeping a view outside. Light-filtering fabrics let in soft light and give privacy. Blackout fabrics block almost all light and are used where darkness is needed, such as in rest or sleep areas.

Q3: Can roller blinds be used in hospitals and clinics?  
A: Yes, they are commonly used in patient rooms, consultation rooms and offices. Wipeable or washable fabrics are preferred, and in some areas, such as mental health units, cordless or ligature-safe operating systems are used instead of cords.

Q4: How do I measure a window for a roller blind?  
A: For an inside mount, measure the width at the top, middle and bottom of the window recess and use the smallest figure, then measure the height. For an outside mount, measure the area to be covered and add overlap on each side.

Q5: How do I clean a roller blind?  
A: Dust it regularly with a soft brush or dry cloth, and wipe marks with a slightly damp cloth and mild soap. Soaking the fabric or pulling hard on the tube should be avoided.

Q6: When should vertical blinds be used instead of roller blinds?  
A: Vertical blinds suit wide windows and sliding doors because the slats rotate to control light and slide to the side. Roller blinds suit standard windows and give a flat, clean look.

### FAQPage schema

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "@id": "https://www.kainternational.co.in/blends.htm#faq",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What is a roller blind and how does it work?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "A roller blind is a single sheet of fabric wound around a tube at the top of a window. It is raised or lowered with a chain, cord or spring mechanism, and sits flat against the window when lowered."
      }
    },
    {
      "@type": "Question",
      "name": "What is the difference between sheer, light-filtering and blackout roller blinds?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Sheer or sunscreen fabrics reduce glare while keeping a view outside. Light-filtering fabrics let in soft light and give privacy. Blackout fabrics block almost all light and are used where darkness is needed, such as in rest or sleep areas."
      }
    },
    {
      "@type": "Question",
      "name": "Can roller blinds be used in hospitals and clinics?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes, they are commonly used in patient rooms, consultation rooms and offices. Wipeable or washable fabrics are preferred, and in some areas, such as mental health units, cordless or ligature-safe operating systems are used instead of cords."
      }
    },
    {
      "@type": "Question",
      "name": "How do I measure a window for a roller blind?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "For an inside mount, measure the width at the top, middle and bottom of the window recess and use the smallest figure, then measure the height. For an outside mount, measure the area to be covered and add overlap on each side."
      }
    },
    {
      "@type": "Question",
      "name": "How do I clean a roller blind?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Dust it regularly with a soft brush or dry cloth, and wipe marks with a slightly damp cloth and mild soap. Soaking the fabric or pulling hard on the tube should be avoided."
      }
    },
    {
      "@type": "Question",
      "name": "When should vertical blinds be used instead of roller blinds?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Vertical blinds suit wide windows and sliding doors because the slats rotate to control light and slide to the side. Roller blinds suit standard windows and give a flat, clean look."
      }
    }
  ]
}
</script>
```

---

## 8. Aluminium Partitions

URL: https://www.kainternational.co.in/aluminium-partition.html

### On-page FAQs

Q1: What is an aluminium partition?  
A: An aluminium partition is a non-load-bearing wall made of an aluminium frame filled with glass, laminated board or other panels. It is used to divide a large space into rooms without building a masonry wall.

Q2: What is the difference between powder-coated and anodised aluminium?  
A: Powder coating applies a coloured paint-like layer that is available in many colours. Anodising is an electrochemical process that thickens the natural oxide layer of the metal, giving a harder, metallic finish in a limited range of tones.

Q3: Where are aluminium partitions used in hospitals?  
A: They are used for doctor cabins, consultation and counselling rooms, reception and billing areas, laboratories and clean-area enclosures. Glass panels let staff see into the room while keeping noise and dust out.

Q4: What glass options are available for aluminium partitions?  
A: Toughened glass is stronger and breaks into small pieces. Laminated glass holds together when cracked and gives better sound reduction. Frosted or film-covered glass adds privacy. The choice depends on safety, privacy and acoustic needs.

Q5: How do aluminium partitions compare with brick or gypsum walls?  
A: Aluminium partitions are lighter, quicker to install and easier to relocate. Sound insulation and fire resistance depend on the specific system, glass and seals used, so those ratings should be confirmed rather than assumed.

Q6: What do I need to know before installing an aluminium partition?  
A: Provide an accurate floor plan, the ceiling height, the layout of doors and glazing, and the level and strength of the floor and ceiling to which the frame will be fixed. Uneven floors or ceilings should be corrected or allowed for.

### FAQPage schema

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "@id": "https://www.kainternational.co.in/aluminium-partition.html#faq",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What is an aluminium partition?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "An aluminium partition is a non-load-bearing wall made of an aluminium frame filled with glass, laminated board or other panels. It is used to divide a large space into rooms without building a masonry wall."
      }
    },
    {
      "@type": "Question",
      "name": "What is the difference between powder-coated and anodised aluminium?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Powder coating applies a coloured paint-like layer that is available in many colours. Anodising is an electrochemical process that thickens the natural oxide layer of the metal, giving a harder, metallic finish in a limited range of tones."
      }
    },
    {
      "@type": "Question",
      "name": "Where are aluminium partitions used in hospitals?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "They are used for doctor cabins, consultation and counselling rooms, reception and billing areas, laboratories and clean-area enclosures. Glass panels let staff see into the room while keeping noise and dust out."
      }
    },
    {
      "@type": "Question",
      "name": "What glass options are available for aluminium partitions?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Toughened glass is stronger and breaks into small pieces. Laminated glass holds together when cracked and gives better sound reduction. Frosted or film-covered glass adds privacy. The choice depends on safety, privacy and acoustic needs."
      }
    },
    {
      "@type": "Question",
      "name": "How do aluminium partitions compare with brick or gypsum walls?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Aluminium partitions are lighter, quicker to install and easier to relocate. Sound insulation and fire resistance depend on the specific system, glass and seals used, so those ratings should be confirmed rather than assumed."
      }
    },
    {
      "@type": "Question",
      "name": "What do I need to know before installing an aluminium partition?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Provide an accurate floor plan, the ceiling height, the layout of doors and glazing, and the level and strength of the floor and ceiling to which the frame will be fixed. Uneven floors or ceilings should be corrected or allowed for."
      }
    }
  ]
}
</script>
```

---

## 9. Monitor Stand

URL: https://www.kainternational.co.in/monitor-stand.html

### On-page FAQs

Q1: What is a wall-mounted monitor stand?  
A: A wall-mounted monitor stand is a bracket or arm fixed to a wall that holds a patient monitor at a convenient height. It keeps the monitor off the floor and frees space on tables and trolleys.

Q2: What should I check before choosing a monitor stand?  
A: Check the monitor's weight and the mounting pattern on its back, the stand's rated load, the reach and swivel range needed, and the wall type. The stand should be rated for more than the monitor's weight.

Q3: What are the different ways to mount a patient monitor?  
A: Monitors can be mounted on a wall bracket, on a bed-head panel or rail, on a mobile trolley, or on a ceiling pendant. The best choice depends on whether the monitor stays in one place or moves with the patient.

Q4: What type of wall is needed for a monitor stand?  
A: A solid masonry or reinforced wall is best. Hollow partitions or plasterboard need a backing plate or fixings into a solid support, because a monitor can be heavy and a weak fixing is a safety risk.

Q5: At what height should a monitor be mounted?  
A: The screen should be visible from where staff normally stand, and usually near eye level. Allowing the arm to swivel and tilt helps staff and patients view the screen without glare.

Q6: What finish is suitable for monitor stands used in hospitals?  
A: Powder-coated steel or stainless steel is commonly used because the surface is smooth and can be wiped with hospital disinfectants. Cable management features help keep cords tidy and off the floor.

### FAQPage schema

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "@id": "https://www.kainternational.co.in/monitor-stand.html#faq",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What is a wall-mounted monitor stand?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "A wall-mounted monitor stand is a bracket or arm fixed to a wall that holds a patient monitor at a convenient height. It keeps the monitor off the floor and frees space on tables and trolleys."
      }
    },
    {
      "@type": "Question",
      "name": "What should I check before choosing a monitor stand?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Check the monitor's weight and the mounting pattern on its back, the stand's rated load, the reach and swivel range needed, and the wall type. The stand should be rated for more than the monitor's weight."
      }
    },
    {
      "@type": "Question",
      "name": "What are the different ways to mount a patient monitor?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Monitors can be mounted on a wall bracket, on a bed-head panel or rail, on a mobile trolley, or on a ceiling pendant. The best choice depends on whether the monitor stays in one place or moves with the patient."
      }
    },
    {
      "@type": "Question",
      "name": "What type of wall is needed for a monitor stand?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "A solid masonry or reinforced wall is best. Hollow partitions or plasterboard need a backing plate or fixings into a solid support, because a monitor can be heavy and a weak fixing is a safety risk."
      }
    },
    {
      "@type": "Question",
      "name": "At what height should a monitor be mounted?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The screen should be visible from where staff normally stand, and usually near eye level. Allowing the arm to swivel and tilt helps staff and patients view the screen without glare."
      }
    },
    {
      "@type": "Question",
      "name": "What finish is suitable for monitor stands used in hospitals?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Powder-coated steel or stainless steel is commonly used because the surface is smooth and can be wiped with hospital disinfectants. Cable management features help keep cords tidy and off the floor."
      }
    }
  ]
}
</script>
```

---

## 10. Furnishing

URL: https://www.kainternational.co.in/furnishing.html

### On-page FAQs

Q1: What are the common curtain heading styles?  
A: Common heading styles include pleated, box pleated, eyelet (ring top), loop and plain styles. Pleated and box pleated heads give a formal, structured look, while eyelet and loop headings hang in soft, regular folds.

Q2: How much fabric do I need for a curtain?  
A: Curtains need fabric wider than the window or track so that they hang in folds. Fullness is usually about one and a half to two times the track width, depending on the heading style and the fabric weight.

Q3: What is the difference between jacquard, self-design, solid and printed fabrics?  
A: Solid fabrics are a single colour. Self-design fabrics have a pattern woven in the same colour. Jacquard fabrics have a more complex pattern woven into the cloth, and printed fabrics have the design applied on top of the cloth.

Q4: Which furnishing fabrics are suitable for hospitals and clinics?  
A: Fabrics for healthcare areas should be washable, durable and flame-retardant, with colours that hide marks. Heavier, tightly woven fabrics usually last longer through repeated laundering.

Q5: How do I measure a window for curtains?  
A: Measure the width of the track or rod and extend it beyond the window on each side so the curtain can clear the glass when open. For length, measure from the track to the sill, below the sill or to just above the floor, depending on the style.

### FAQPage schema

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "@id": "https://www.kainternational.co.in/furnishing.html#faq",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What are the common curtain heading styles?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Common heading styles include pleated, box pleated, eyelet (ring top), loop and plain styles. Pleated and box pleated heads give a formal, structured look, while eyelet and loop headings hang in soft, regular folds."
      }
    },
    {
      "@type": "Question",
      "name": "How much fabric do I need for a curtain?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Curtains need fabric wider than the window or track so that they hang in folds. Fullness is usually about one and a half to two times the track width, depending on the heading style and the fabric weight."
      }
    },
    {
      "@type": "Question",
      "name": "What is the difference between jacquard, self-design, solid and printed fabrics?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Solid fabrics are a single colour. Self-design fabrics have a pattern woven in the same colour. Jacquard fabrics have a more complex pattern woven into the cloth, and printed fabrics have the design applied on top of the cloth."
      }
    },
    {
      "@type": "Question",
      "name": "Which furnishing fabrics are suitable for hospitals and clinics?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Fabrics for healthcare areas should be washable, durable and flame-retardant, with colours that hide marks. Heavier, tightly woven fabrics usually last longer through repeated laundering."
      }
    },
    {
      "@type": "Question",
      "name": "How do I measure a window for curtains?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Measure the width of the track or rod and extend it beyond the window on each side so the curtain can clear the glass when open. For length, measure from the track to the sill, below the sill or to just above the floor, depending on the style."
      }
    }
  ]
}
</script>
```

---

## 11. Hospital Furniture

URL: https://www.kainternational.co.in/hospital-furniture.html

### On-page FAQs

Q1: What furniture is commonly used in hospital wards?  
A: Common items include patient beds, bedside lockers, overbed tables, visitor chairs, examination couches, treatment trolleys, stools and privacy screens.

Q2: Which materials are used for hospital furniture?  
A: Powder-coated mild steel, stainless steel, aluminium, laminate and moulded plastic are common. The choice depends on the strength needed, cleaning products used and resistance to rust and wear.

Q3: What features should hospital furniture have for infection control?  
A: Surfaces should be smooth, non-porous and free from deep joints or cracks where dirt can collect, so they can be wiped with hospital disinfectants. Lockable castors and rounded edges also help with safe cleaning and handling.

Q4: What does ergonomic hospital furniture mean?  
A: It means furniture designed to reduce strain on patients and staff, such as height-adjustable beds and tables, adjustable backrests, correct seat heights and handles at comfortable positions.

Q5: How do I check the load capacity of hospital furniture?  
A: Look for the safe working load given by the manufacturer for items such as beds, trolleys, stools and examination couches, and choose a rating that comfortably exceeds the expected use, including heavier patients.

### FAQPage schema

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "@id": "https://www.kainternational.co.in/hospital-furniture.html#faq",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What furniture is commonly used in hospital wards?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Common items include patient beds, bedside lockers, overbed tables, visitor chairs, examination couches, treatment trolleys, stools and privacy screens."
      }
    },
    {
      "@type": "Question",
      "name": "Which materials are used for hospital furniture?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Powder-coated mild steel, stainless steel, aluminium, laminate and moulded plastic are common. The choice depends on the strength needed, cleaning products used and resistance to rust and wear."
      }
    },
    {
      "@type": "Question",
      "name": "What features should hospital furniture have for infection control?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Surfaces should be smooth, non-porous and free from deep joints or cracks where dirt can collect, so they can be wiped with hospital disinfectants. Lockable castors and rounded edges also help with safe cleaning and handling."
      }
    },
    {
      "@type": "Question",
      "name": "What does ergonomic hospital furniture mean?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "It means furniture designed to reduce strain on patients and staff, such as height-adjustable beds and tables, adjustable backrests, correct seat heights and handles at comfortable positions."
      }
    },
    {
      "@type": "Question",
      "name": "How do I check the load capacity of hospital furniture?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Look for the safe working load given by the manufacturer for items such as beds, trolleys, stools and examination couches, and choose a rating that comfortably exceeds the expected use, including heavier patients."
      }
    }
  ]
}
</script>
```

---

## 12. Enquiry

URL: https://www.kainternational.co.in/enquiry.html

### On-page FAQs

Q1: What information is needed to get an accurate quotation for hospital curtains?  
A: Provide the number of curtains, finished width and drop, fabric type, colour, flame-retardant requirement, mesh panel details, heading style, and whether hooks and carriers are required. Measurements for each bed bay avoid errors.

Q2: What details are needed for a cubicle track quotation?  
A: Share a layout sketch showing each track run, the total length, the number and angle of bends, the ceiling type and height, and whether IV carriers or a removal gate are required.

Q3: How do I measure a ward for curtains and tracks?  
A: Measure the bed bay width and depth, the ceiling height, and the positions of lights, sprinklers and air vents that could obstruct the track. Mark the planned track route on a floor plan before measuring the lengths.

Q4: What is fabric GSM and why does it matter?  
A: GSM stands for grams per square metre and shows the weight of the fabric. A heavier fabric usually drapes better and lasts longer, but it also costs more and is heavier on the track, so the GSM should suit the use.

Q5: What should I compare when reviewing quotations for ward furnishings?  
A: Compare the fabric or material specification, flame-retardant details, track thickness and finish, hardware included, installation scope, warranty terms and delivery period, rather than only the total price.

Q6: When is a site visit useful before placing an order?  
A: A site visit is useful when the ceiling is high or uneven, when there are obstructions, or when the layout is complex. It confirms the measurements and fixing method before production starts.

### FAQPage schema

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "@id": "https://www.kainternational.co.in/enquiry.html#faq",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What information is needed to get an accurate quotation for hospital curtains?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Provide the number of curtains, finished width and drop, fabric type, colour, flame-retardant requirement, mesh panel details, heading style, and whether hooks and carriers are required. Measurements for each bed bay avoid errors."
      }
    },
    {
      "@type": "Question",
      "name": "What details are needed for a cubicle track quotation?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Share a layout sketch showing each track run, the total length, the number and angle of bends, the ceiling type and height, and whether IV carriers or a removal gate are required."
      }
    },
    {
      "@type": "Question",
      "name": "How do I measure a ward for curtains and tracks?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Measure the bed bay width and depth, the ceiling height, and the positions of lights, sprinklers and air vents that could obstruct the track. Mark the planned track route on a floor plan before measuring the lengths."
      }
    },
    {
      "@type": "Question",
      "name": "What is fabric GSM and why does it matter?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "GSM stands for grams per square metre and shows the weight of the fabric. A heavier fabric usually drapes better and lasts longer, but it also costs more and is heavier on the track, so the GSM should suit the use."
      }
    },
    {
      "@type": "Question",
      "name": "What should I compare when reviewing quotations for ward furnishings?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Compare the fabric or material specification, flame-retardant details, track thickness and finish, hardware included, installation scope, warranty terms and delivery period, rather than only the total price."
      }
    },
    {
      "@type": "Question",
      "name": "When is a site visit useful before placing an order?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "A site visit is useful when the ceiling is high or uneven, when there are obstructions, or when the layout is complex. It confirms the measurements and fixing method before production starts."
      }
    }
  ]
}
</script>
```

---

## 13. About Us

URL: https://www.kainternational.co.in/about-us.html

### On-page FAQs

Q1: What is hospital furnishing?  
A: Hospital furnishing covers the fabrics, fittings and furniture used inside healthcare buildings, such as privacy curtains, curtain tracks, blinds, partitions, IV hangers, monitor stands, beds and bedside furniture.

Q2: Why is infection control important when choosing ward furnishings?  
A: Items that are touched often, such as curtains and furniture surfaces, can carry germs between patients. Studies of hospital rooms have found bacteria on a high share of privacy curtains, so materials that can be washed, wiped and replaced on a schedule are preferred.

Q3: What does a customised or made-to-measure hospital product mean?  
A: It means the product is made to the sizes, colours, fabrics and fittings specified for a particular room or building rather than from a fixed stock size. This is common for curtains, tracks and partitions because room sizes differ.

Q4: What documents should a hospital ask for when buying ward furnishings?  
A: Useful documents include the material specification, flame-retardant or fabric test details, washing instructions, load ratings for hangers and stands, the installation scope and the warranty terms.

Q5: Which hospital products need installation by trained fitters?  
A: Cubicle tracks, IV hangers, air curtains, aluminium partitions and wall-mounted monitor stands need to be fixed to the building structure. Poor fixing can cause failures, so installation should follow the manufacturer's instructions.

### FAQPage schema


<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "@id": "https://www.kainternational.co.in/about-us.html#faq",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What is hospital furnishing?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Hospital furnishing covers the fabrics, fittings and furniture used inside healthcare buildings, such as privacy curtains, curtain tracks, blinds, partitions, IV hangers, monitor stands, beds and bedside furniture."
      }
    },
    {
      "@type": "Question",
      "name": "Why is infection control important when choosing ward furnishings?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Items that are touched often, such as curtains and furniture surfaces, can carry germs between patients. Studies of hospital rooms have found bacteria on a high share of privacy curtains, so materials that can be washed, wiped and replaced on a schedule are preferred."
      }
    },
    {
      "@type": "Question",
      "name": "What does a customised or made-to-measure hospital product mean?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "It means the product is made to the sizes, colours, fabrics and fittings specified for a particular room or building rather than from a fixed stock size. This is common for curtains, tracks and partitions because room sizes differ."
      }
    },
    {
      "@type": "Question",
      "name": "What documents should a hospital ask for when buying ward furnishings?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Useful documents include the material specification, flame-retardant or fabric test details, washing instructions, load ratings for hangers and stands, the installation scope and the warranty terms."
      }
    },
    {
      "@type": "Question",
      "name": "Which hospital products need installation by trained fitters?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Cubicle tracks, IV hangers, air curtains, aluminium partitions and wall-mounted monitor stands need to be fixed to the building structure. Poor fixing can cause failures, so installation should follow the manufacturer's instructions."
      }
    }
  ]
}
</script>


---

## 14. Products

URL: https://www.kainternational.co.in/products.html

### On-page FAQs

Q1: Which products are used to separate patient areas?  
A: Privacy curtains on cubicle tracks give flexible, low-cost separation. Aluminium and glass partitions give fixed, more private separation with better sound reduction. Many hospitals use curtains in wards and partitions for cabins and consultation rooms.

Q2: Which products help manage entrances and doorways?  
A: Air curtains and PVC strip curtains are the two main choices. Air curtains leave the opening clear, while PVC strips provide a visible, physical barrier and are often used for cold rooms and service entrances.

Q3: Which products hold medical equipment off the floor?  
A: IV hangers hold infusion bags overhead, and wall-mounted or rail-mounted stands hold patient monitors. Both reduce clutter around the bed and keep the floor clear for staff movement and cleaning.

Q4: Which window coverings are suitable for hospitals?  
A: Roller blinds and vertical blinds in wipeable or washable fabrics are common. Cordless or safety-rated operating systems are preferred in areas where cords could be a hazard.

Q5: How do I choose between a curtain and a partition?  
A: Choose a curtain when the space needs to be opened and closed, the budget is limited or the layout may change. Choose a partition when permanent separation, sound reduction or a clear view through glass is needed.

Q6: Which products need ceiling fixing?  
A: Cubicle tracks, ceiling IV hangers and air curtains installed above doorways usually require fixing to a structural ceiling or support. The ceiling type and load should be checked before ordering.

### FAQPage schema


<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "@id": "https://www.kainternational.co.in/products.html#faq",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "Which products are used to separate patient areas?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Privacy curtains on cubicle tracks give flexible, low-cost separation. Aluminium and glass partitions give fixed, more private separation with better sound reduction. Many hospitals use curtains in wards and partitions for cabins and consultation rooms."
      }
    },
    {
      "@type": "Question",
      "name": "Which products help manage entrances and doorways?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Air curtains and PVC strip curtains are the two main choices. Air curtains leave the opening clear, while PVC strips provide a visible, physical barrier and are often used for cold rooms and service entrances."
      }
    },
    {
      "@type": "Question",
      "name": "Which products hold medical equipment off the floor?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "IV hangers hold infusion bags overhead, and wall-mounted or rail-mounted stands hold patient monitors. Both reduce clutter around the bed and keep the floor clear for staff movement and cleaning."
      }
    },
    {
      "@type": "Question",
      "name": "Which window coverings are suitable for hospitals?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Roller blinds and vertical blinds in wipeable or washable fabrics are common. Cordless or safety-rated operating systems are preferred in areas where cords could be a hazard."
      }
    },
    {
      "@type": "Question",
      "name": "How do I choose between a curtain and a partition?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Choose a curtain when the space needs to be opened and closed, the budget is limited or the layout may change. Choose a partition when permanent separation, sound reduction or a clear view through glass is needed."
      }
    },
    {
      "@type": "Question",
      "name": "Which products need ceiling fixing?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Cubicle tracks, ceiling IV hangers and air curtains installed above doorways usually require fixing to a structural ceiling or support. The ceiling type and load should be checked before ordering."
      }
    }
  ]
}
</script>


---

## 15. Contact

URL: https://www.kainternational.co.in/contact.html

### On-page FAQs

Q1: What should I prepare before requesting a quotation or site visit?  
A: Prepare the type of product, approximate quantities, room or ward dimensions, ceiling height and type, preferred colours or materials, and the target installation date. A simple sketch or floor plan speeds up the process.

Q2: What drawings or photos help when requesting a quotation?  
A: A floor plan marked with the proposed curtain, track or partition locations is the most useful, followed by clear photos of the ceiling, windows and door openings. Photos help identify obstructions such as lights and pipes.

Q3: What usually happens during a site measurement visit?  
A: The installer checks the measurements, ceiling and wall conditions, fixing points and obstructions, and confirms the layout with the facility team. Any changes needed to the design are noted before the quotation is finalised.

Q4: How is installation planned in a hospital that is in use?  
A: Work is often planned in phases, ward by ward or area by area, during quieter periods, so that patient care is not disturbed. Noise, dust and access routes should be agreed with the facility team in advance.

Q5: What are the usual steps from enquiry to installation?  
A: The usual steps are sharing requirements, site measurement, quotation, approval of samples or drawings, production, delivery and installation. Each step should be confirmed in writing, including the installation scope.

### FAQPage schema


<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "@id": "https://www.kainternational.co.in/contact.html#faq",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What should I prepare before requesting a quotation or site visit?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Prepare the type of product, approximate quantities, room or ward dimensions, ceiling height and type, preferred colours or materials, and the target installation date. A simple sketch or floor plan speeds up the process."
      }
    },
    {
      "@type": "Question",
      "name": "What drawings or photos help when requesting a quotation?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "A floor plan marked with the proposed curtain, track or partition locations is the most useful, followed by clear photos of the ceiling, windows and door openings. Photos help identify obstructions such as lights and pipes."
      }
    },
    {
      "@type": "Question",
      "name": "What usually happens during a site measurement visit?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The installer checks the measurements, ceiling and wall conditions, fixing points and obstructions, and confirms the layout with the facility team. Any changes needed to the design are noted before the quotation is finalised."
      }
    },
    {
      "@type": "Question",
      "name": "How is installation planned in a hospital that is in use?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Work is often planned in phases, ward by ward or area by area, during quieter periods, so that patient care is not disturbed. Noise, dust and access routes should be agreed with the facility team in advance."
      }
    },
    {
      "@type": "Question",
      "name": "What are the usual steps from enquiry to installation?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The usual steps are sharing requirements, site measurement, quotation, approval of samples or drawings, production, delivery and installation. Each step should be confirmed in writing, including the installation scope."
      }
    }
  ]
}
</script>


---

## Implementation notes

1. Show the same text on the page. Put the Q&A in a visible FAQ section. Do not add schema questions that are not visible on the page.
2. One FAQPage block per page. Remove old FAQPage scripts before adding these. Keep Organization, LocalBusiness, Product and BreadcrumbList schema as separate blocks.
3. Close every script tag. The earlier cubicle-tracks page had a missing closing `</script>` and an extra one after LocalBusiness, and the old products block had a stray character after the last brace. Check these when pasting.
4. `blends.htm` vs `blends.html`. The Roller Blinds `@id` here uses the URL you gave (`/blends.htm`). If the live page is `/blends.html`, change the path in the `@id`.
5. `contact.html`. Your old second products block carried contact-page schema. A Contact section is included so it can go on `contact.html`.
6. Validate. Test each URL in Google's Rich Results Test and the Schema Markup Validator after publishing. Note that Google now shows FAQ rich results only for a limited set of sites, so the main benefit is clear structured content, not a guaranteed rich result.
7. Review for your products. The answers are general. If your products differ (for example, track material or hook count), adjust the wording on both the page and the schema together so they stay identical.
