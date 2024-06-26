# RFID Reader Testing and Cloning

In this project, I will demonstrate the capability of a simple RFID Reader/Writer, easily accessible at Walmart for $7.09 as you can see here:

**Manunclaims Handheld RFID Writer, Handheld 125KHz RFID Duplicator Copier Writer Programmer Reader EM4305 ID Cards**
![RFID_Reader_Writer](https://github.com/nivvoudit/RFID_Testing/assets/25519970/4e6ba246-3fad-4cbe-8ea3-4946e49f458f)

# Important Note:
**Legal Consequences:**
*Engaging in unauthorized RFID cloning is illegal and can result in severe penalties, including fines and imprisonment. Laws such as the Computer Fraud and Abuse Act (CFAA) and various state-specific regulations criminalize the unauthorized access and replication of RFID data, aiming to protect individuals and institutions from these disruptive activities. Penalties vary based on the severity of the offense, the extent of damage caused, and the jurisdiction, but they underscore the serious nature of this cybercrime.*

**Understanding the legal ramifications and implementing strong security measures are essential to safeguarding RFID technology from malicious exploitation.**


# "What is RFID" you say? And why should you care?

**From the badges that you use to clock in at work, to your bank cards, your travel cards for the bus/train, your passport, your medical information and dare I even mention...your wristbands at Coachella/Shaky Knees/your favorite Coldplay/Taylor Swift concert? Yes, they are (mostly) RFID based.**

Radio Frequency Identification (RFID) is a technology that uses electromagnetic fields to automatically identify and track tags attached to objects. These tags contain electronically stored information which can be read from a distance using an RFID reader. RFID is widely used in various applications such as inventory management, access control, contactless payments, and asset tracking. The technology enables quick and accurate data capture without the need for direct line-of-sight or physical contact, making it an efficient solution for automating identification processes and enhancing operational efficiency in many industries.

# My Process
I will attempt to read an RFID proximity card and then attempt to clone it using another card of the same type (I will use a card, but as I will explain later below - there are also other types of media you can use to access resources via the RFID signal.)

*Proximity cards (also known as prox cards and key cards) are a type of smart card that make it easy to control access to and within a facility. They are physical devices containing a small antenna and programmed with credentials and are used in security systems for electronic authentication i.e your typical key card that you would use to access your facility's front door and otherwise access other resources associated with the information stored on that card.*


# **Reading the Source Card**......**SUCCESS!**
![RFID_Clone](https://github.com/nivvoudit/RFID_Testing/assets/25519970/4fc339b9-232b-49cc-bddb-caf6df833b98)


Now that we have captured the data from the source card, let's see if we can write it to a card of a similar type. 


# **Writing data from the source card to a CLONE card**.....**SUCCESS!**
![RFID_Write](https://github.com/nivvoudit/RFID_Testing/assets/25519970/18befdff-4106-412e-90d9-58907807e029)


For the purposes of this demonstration, I used a blank, similar RFID card. 

# However...

**There are also many different types of writeable media available e.g. key fobs, tags, wristbands and so forth - from travel cards, concert/event tags, to even medical patient wristbands.**

![OtherTypes](https://github.com/nivvoudit/RFID_Testing/assets/25519970/bcab6dd7-1418-40e7-9a69-964bd7b92e1e)


There was even a case where someone creatively turned his RFID chip into a wand (while dressed as Gandalf from Lord of the Rings), tapping his wand on the card readers to access travel:

![Wand_Clone_RFID](https://github.com/nivvoudit/RFID_Testing/assets/25519970/e6ef4f45-ad6a-42ae-a24e-f4cf1038530b)


# The Risks of RFID Cloning:
Radio Frequency Identification (RFID) technology is widely used in various sectors due to its convenience and efficiency in tracking and authenticating items and individuals. However, the ability to easily read and clone RFID devices poses significant cybersecurity risks, potentially causing severe disruptions in critical areas such as travel, banking, and healthcare.

**Travel**: RFID technology is commonly used in passports and boarding passes. Cloning these RFID tags can allow malicious actors to bypass security checks, leading to unauthorized access to secure areas, identity theft, and even the trafficking of illicit goods. Such breaches can compromise the safety of travelers and the integrity of border control systems.

**Banking**: Contactless payment cards and keycards utilize RFID technology for quick and secure transactions. Cloning these cards can lead to unauthorized access to financial accounts, resulting in significant financial losses for individuals and institutions. Furthermore, it undermines the trust in contactless payment systems, impacting the overall security of financial transactions.

**Medical**: RFID tags are used in patient identification, medical equipment tracking, and pharmaceutical management. Cloning these tags can result in severe consequences, including incorrect patient treatment, unauthorized access to medical facilities, and the distribution of counterfeit medications. This not only jeopardizes patient safety but also disrupts the integrity of healthcare services.

As RFID technology continues to integrate into our daily lives, it is crucial to address its vulnerabilities and implement robust security measures to prevent cloning and unauthorized access. Ensuring the integrity and security of RFID systems is essential to protect sensitive information and maintain trust in these critical sectors.

# Available Solutions

There are currently available solutions to protect malicious actors from cloning RFID devices. Most of these solutions involve a physical, protective layer surrounding the RFID source:

![Solutions](https://github.com/nivvoudit/RFID_Testing/assets/25519970/565ee377-3aeb-4b00-990d-40b452b31ae6)

# More secure alternatives

I will explore more secure, alternative solutions in upcoming projects including cards using different technologies (e.g. MiFare EV2). Stay tuned and thanks for reading!




