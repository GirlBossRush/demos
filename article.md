In late 2017 a group of university researchers discovered a "Meltdown", a critical security flaw described as melting the virtual barriers that keep programs from accessing each other's data. Coincidentally, three other independent research groups have discovered similar security flaws in just a few months of each other, sparking widespread panic in the tech world.

Unlike most reports of software vulnerabilities, Meltdown originates from a common defect in computer processors — the silicon chips that power your devices. Shortly after researchers submitted their findings to Intel, the chip manufacturer was dealt another blow. Researchers Paul Kocher and the team at Project Zero independently reported "Spectre", a similar hardware defect with devastating security implications.

Tech companies are now scrambling to find a solution to patch the vulnerabilities affecting most computers, tablets, and smart phones made in the past 30 years.

# A Ghost In The Machine

Spectre makes use of a defect in a processor's *speculative execution*, a technical term used to describe the predictions computers make to increase performance. Whether it's opening the Facebook app; taking a selfie; or checking your email; the tasks are common enough that a processor can predict what a user will do before they even decide to. If processor guesses correctly, things feel slightly faster.

Spectre attacks manipulate other apps into accidentally revealing their own private data. Like Meltdown, both types of attack could theoretically be used to find sensitive information as it's passed through the computer's processor. A simple flashlight app could use these processor flaws to secretly read an account number in a recently used bank app. Discovering when a malicious app is using these techniques is incredibly difficult, even with an anti-virus.

# Imperfect Solutions

Since publication of the research, companies such as Microsoft, Apple, and Intel have deployed a dizzying number of software updates to work around the hardware defects. Unfortunately reports of computer crashes and reduced performance have been in high frequency. Researchers explain that the software updates come at a price: slower hardware.

>...we're looking at a ballpark figure of five to 30 per cent slow down, depending on the task and the processor model.
[The Register](https://www.theregister.co.uk/2018/01/02/intel_cpu_design_flaw/)

The trade off between speed and security may not be available to all consumers. Millions of older, unsupported devices will most likely not receive any updates. Hardware manufactures may instead recommend buying newer models to lower the chances of becoming a victim to Meltdown and Spectre attacks.

Researchers are still learning more about the damage done and software updates are still being released. Computers have been vulnerable to Meltdown and Spectre for decades and many will remain unpatched. You can reduce your chances of being a victim by taking steps to protect your digital identity -- starting with your email account. A memorable, lengthy and unique password for each online account can significantly decrease the chances of an attacker taking control. Many online services can also send a special code to your phone to verify that your password isn't being use without your permission. This extra verification is recommended for other services such as your bank, Facebook, Instagram, and Dropbox.

## Learn more about handling Meltdown and Spectre

[An detailed explanation of the vulnerabilities and available updates](https://spectreattack.com/) — Graz University of Technology

[How to set up two-factor authentication on all your online accounts](https://www.theverge.com/2017/6/17/15772142/how-to-set-up-two-factor-authentication) — The Verge

