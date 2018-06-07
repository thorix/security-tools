# BSides Denver, May 11 & 12 2018
  https://www.bsidesden.org/
  https://bsidesden2018.sched.com/

## Hacker Carpet Bomb
  Andy "rainmaker" Thompson

  Abstract: This talk is series of live demonstrations of real-world attacks that organizations see on a daily basis. The goal is to present as many possible live demos of exploits and attacks as possible in the time alloted. Attacks will include stealing hashes off the wire with Responder & Inveigh, Poison Tap, Bash Bunny, MouseJack and more!
  Outline:
  * Introduction
  * Explanation of the Cyber Kill-Chain
  * Poison Tap
  * Responder & Inveigh
  * Bash Bunny
  * MouseJack
  * WifiPineapple
  * USB Killer
  * Mitigation Techniques
  * Q&A

## Converge: A Cross Discipline Approach to IR and Breach Investigations (and Lessons Learned)
  Douglas Brush

  How non-traditional litigation tools can assist cyber investigators with Incident Response and data breaches.

  With the increased use of SaaS, IaaS, and PaaS platforms, organizations are shoveling more compute, applications, and data into the cloud from on-premises solutions. However, answering cloud governance and access control questions such as “What data do I have?," "Where is my data stored?," Who has access to my data?,” has become challenging. Often, it is because data is out of sight and out of mind.. Additionally, during a breach, these questions can impede an investigation that is already challenged by decentralized logging, access rights, large volumes of data review, and the inability to physically access the environment.

  This presentation will walk thought the current challenges faced by defenders and IR investigators, and offer solutions that call on a variety of cyber security, digital forensic and incident response, and eDiscovey talents. We will step through a case example where the convergence of these disciplines allowed an organization to effectively investigate a complex cloud data breach, and comply with regulatory notification requirements.

## Seive of Stackstrings: Hunting, Triaging, and Deobfuscating Stackstrings in Malware
  William Ballenthin, Reverse Engineer, FireEye

  Like packing, the presence of obfuscated data in executable files often indicates a malicious disposition. If we can find a way to detect obfuscation techniques in a feed of suspicious files, then we can potentially identify new strains of malware as they are first collected.

  During this presentation, we’ll focus on stackstrings, a common technique that mixes code and data to break-up contiguous data and evade naïve malware analysis tools. I’ll demonstrate why FLOSS (the FireEye Labs Obfuscated String Solver) can pull out stackstrings of a file, but is not a good fit for hunting stackstrings at scale. Instead, we’ll see how to develop Yara rules that match C code constructs in compiled binaries. Finally, I’ll share an introduction to the Unicorn CPU engine and teach the audience how to emulate select portions of malware samples to deobfuscate stackstrings. We’ll see that the proposed solution can detect and decode stackstrings from thousands of samples per second, easily consuming the entire public VirusShare corpus (30 million samples).

  The audience will enjoy a real-world case study of scaling a hunting technique by relying on high-performance, open-source tools. We’ll see that with very few lines of code, we can implement a novel, yet effective, sieve for malware executable files. If all goes well, the audience will leave with renewed confidence to hunt for new malware families using Yara alongside binary code emulation.

## Ducky-in-the-middle: Injecting keystokes into plaintext protocols
  Esteban Rodriguez, n00py, n00py1(twitter)

  This presentation will cover the research I preformed analyzing the protocols used for HippoRemote, and iPhone application that turns your phone into an mouse/trackpad/keyboard and Synergy, software for remotely controlling multiple systems with a single mouse and keyboard.   By intercepting these protocols on the wire, an attacker can inject malicious keystrokes to compromise a user's workstation.

  https://www.n00py.io/2017/01/control-your-mac-with-an-iphone-app-an-analysis-of-hipporemote/
  https://www.n00py.io/2017/03/compromising-synergy-clients-with-a-rogue-synergy-server/

## GreatSCT: Gotta Catch 'Em AWL
  Chris "Lopi" Spehn

  Great Scott Marty, we went all the way back to 1995! The project is called Great SCT (Great Scott). GreatSCT is an open source project to generate application whitelisting (AWL) bypasses. This tool is intended for BOTH red and blue team. Blue team can benefit by testing the publicly known application whitelisting bypass methods. We will review the most common application whitelisting bypass methods and how to utilize these methods with GreatSCT.

## Adversary Simulation Using Metasploit and ATT&CK
  Hristo Asenov

  With an ever-increasing landscape of vulnerabilities and threats, it becomes imperative that Blue Teams are able to test their defensive solutions and implementations. We propose an adversary framework which is able to simulate a realistic threat actor that uses a playbook of scenarios to launch, escalate and persist without manual input. Additionally the framework is able to detect and react to a defender's actions. The framework uses MITRE's ATT&CK to map tactics and techniques to specific Metasploit modules, whom it communicates with over its RPC API. It is currently being used in production and is used for cybersecurity scenarios.

## Collect and SOAR all the things
  Colin Blumer, SSA, Splunk

  Visibility and Analytics are key, but how can you act on all of that data in an automated, orchestrated, and consistent way?

## WiFiPi: Rasperries and Radios and Antennas, oh my!
  Ray Doyle, Principal Penetration Testing Consultant, Secureworks

  Tired of carrying heavy backpacks? Wondering why wireless assessments can be such a drag? Script kiddies making fun of you for your outdated tools and techniques? If so, then the WiFiPi is for you!

  In this talk, I'll discuss using Raspberry Pis to assess wireless networks. Your Pi can be a valuable tool in pentesting, remote monitoring, managing networks, signal testing, and more.

  If you're new to Raspberry Pis, this talk will give you general methodology for wireless assessments as well as tips for making your gear more portable. If you're not into wireless testing, then hopefully you'll come away with some other half-baked ideas for all of those Pis that we all have Pi-ling up!

## Why Hackers Still Get In
  Trevor O'Donnal, B1tWr4ngl3r, Senior Security Analyst, Rapid7

  In my talk, i give examples of methods hackers (and penetration testers) use to penetrate modern corporate networks in spite of the millions of dollars that have been spent on countermeasures and security hardware. I demonstrate several techniques we use to exploit corporate blind spots and discuss the most commonly overlooked attack vectors.
