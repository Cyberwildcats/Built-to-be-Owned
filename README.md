# Built-to-be-Owned
Teaching students offensive and defensive cyber security by way of them building their own infrastructure to protect from adversaries

## Flow
This game follows a series of phases.  

| Phase | Type | Description|
|---|---|---|
|Build It| Constructive| build the systems in the game environment|
* *Discover It (Offensive)*  - discover the systems others built
* *Access It (Offensive)* - access other the systems others built
* *Command It (Offensive)* - establish control of the systems others built
* *Persist It (Offensive)* - maintain control of the systems others built
* *Detect It (Defensive)* - detect those who are now in your system
* *Evade It (Offensive)* - hide your presense from those detecting you in their systems
* *Deny It (Defensive)* - kick out those who are in your systems
* *Destroy It (Offensive)* - destroy others' systems that you still control 

Most phases will be completed before the next one begins, though some may run concurrently.  Each phase will have hot wash meetings during and afterwards to maximize learning.

## Phases

### Build it

> Build it and they will come.

---
Construction Phase

---

Students build a Linux server and install two different services on it (each service can only be installed X times during a given game).  They will have 2 weeks to do this.

[Buid It Rules and Instructions](Phases/BuildIt.md)

### Discover it

> Explore the world around you.

---
Offensive phase

*MITRE ATT&CK Tactic:*  [Discovery](https://attack.mitre.org/tactics/TA0007/)

*The adversary is trying to figure out your environment.*

---

After all students have built their respective servers, the coach will scan the network and formulate questions to put into CTFd.  

[Discover It Rules and Instructions](Phases/DiscoverIt.md)

###  Access it 

> Enter freely and of your own accord.

---

Offensive phase

*MITRE ATT&CK Tactic:*  [Initial Access](https://attack.mitre.org/tactics/TA0001/)

*The adversary is trying to get into your network.* 

---

Students will acquire initial access to other student’s systems.

[Access It Rules and Instructions](Phases/AccessIt.md)

### Command it 

> Control is aught but an illusion.

---

Offensive phase

*MITRE ATT&CK Tactic:* [Command and Control](https://attack.mitre.org/tactics/TA0011/)

*The adversary is trying to communicate with compromised systems to control them.*

---

Students will establishg Command and Control of other student’s systems that they have access to.

[Command It Rules and Instructions](Phases/CommandIt.md)

### Persist it 

> Paralyze resistance with persistence

---

Offensive Phase

*MITRE ATT&CK Tactic:* [Persistence](https://attack.mitre.org/tactics/TA0003/)

*The adversary is trying to maintain their foothold.*

---

Students will establish persistence in other students’ systems to avoid expulsion

[Persist It Rules and Instructions](Phases/PersistIt.md)

### Detect it 

> You can't defend. You can't prevent. The only thing you can do is detect and respond.

---

Defensive Phase

---

Find the others in your systems.

[Detect It Rules and Instructions](Phases/DetectIt.md)

### Evade it 

> 

---
Offensive Phase

*MITRE ATT&CK Tactic:* [Defense Evasion](https://attack.mitre.org/tactics/TA0005/)

---
hiding from the other students’ attempts to detect them)

[Evade It Rules and Instructions](Phases/EvadeIt.md)

### Deny it 

> Denial ain't just a river in Egypt. 

---
Defensive Phase

---

Try and eliminate the access others’ have by eliminating their Persistence.

[Deny It Rules and Instructions](Phases/DenyIt.md)


### Destroy it 

---
Offensive Phase

*MITRE ATT&CK Tactic:* [Impact](https://attack.mitre.org/tactics/TA0040/)

*The adversary is trying to manipulate, interrupt, or destroy your systems and data.*

---

The final phase - students are given permission to delete/disable any systems they still have access to.

[Destroy It Rules and Instructions](Phases/DestroyIt.md)