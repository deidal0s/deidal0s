```python


class AboutMe:

    def __init__(
            self, 
            age, 
            from_, 
            stationed, 
            working
        ):
        self.age = "18"
        self.from_ = "Greece"
        self.stationed = "Germany"
        self.working = "Lead Penetration Tester"
        self.company = "Airbus Defense and Space"

    def __repr__(
            self
        ):
        return "AboutMe(age={}, from={}, stationed={}, working={})".format(
            self.age,
            self.from_,
            self.stationed,
            self.working
        )

    def __str__():

        about_me = {
        "about": """
        My name is George and I am also known as Deidalos, im 18 years old and i major in Cyber Security,
        Computer / Data Science, Machine Learning, Software Engineering and Robotic. I am aspiring to work 
        at NSA or IC3 as a Security Researcher and at Google, Facebook or Apple as a Junior Software Engineer.
        I am always working on new Projects despite how hard they are. I always have new ideas for my Projects 
        and my Work. At the moment I am focused on low level Development and low level Capture The Flags and 
        King Of The Hills (in general everything that has to do with low level Dev and Hacking) event and matches. 
        In these past five years I was doing various Bug Bounties for many different companies, I found many different 
        bugs, exploits and 0days for Discord, Instagram, Sleek, Twitter, Lieferando, OBS, Government Websites (Confidential)
        (Some POCs and Exploits can be found at my Youtube Channel and at my Github repositories) and took part in various 
        Cyber Security events through out the years of my Journey.I am always on the lookout for new projects to work on and
        new people to collaborate with.Do check out my repositories and feel free to reach out if you would like to work on 
        any of my existing projects or if you think that I would be a good fit in your project. Im always glad for every 
        single information i get and learn about stuff i don't know."""
    }

        edv_knowledge = {
            "Computer Science"      : "Fictional Timetableing System, OCR, FR-CCTV(Face Recognition AI)",
            "Data Science"          : "Sentiment Analysis, Natural Language Processing, Machine Learning",
            "Software Engineering"  : "Web Browser Development, Android Development, iOS Development",
            "Machine Learning"      : "Neural Networks, Deep Learning, Reinforcement Learning",
            "Robotic"               : "Robotic Arm, Robotic Head, Robotic Leg, Robotic Hand",
            "Hacking"               : "Penetration Testing, Vulnerability Analysis\n"
                                      "Reversing, Low Level Hacking ( Kernel, ...\n"
                                      "Web Exploitation, Hardware Hacking(Wallet, USB, INP Devicesn"
                                      "Bug Hunting, IOT Hacking, Binary Exploitation, Car Hacking(sort of?)",
            "Cyber Security"        : "Vulnerability Analysis",
            "Cryptography"          : "Cryptography, Encryption, Decryption",
            "Networking"            : "Networking, Network Security, Network Monitoring, VPNS, Packet Poisoning",
            "Hardware"              : "Embedded Systems, Hardware Security",
            "Low Level"             : "Operating System, Bootloader, DCA, Chipsets, MBU, Motherboards (Fail)",
            "Fullstack, Dev Ops"    : "Exploitation(modules) Website, Blog, Portofolio, Databases",
            "MS-PowerPoint"         : "Presentations, Slides, Animations",
            "MS-Excel"              : "Spreadsheets, Tables, Charts",
            "MS-Word"               : "Documents, Pages, Presentations",
            "MS-Access"             : "Access Databases, Access Forms"
        }

        return edv_knowledge
        return about_me["about"]
```
