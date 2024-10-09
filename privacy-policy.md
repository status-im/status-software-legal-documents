**Status Software \- Privacy Policy**

Last update: 30 September 2024

This Status Software \- Privacy Policy (“**Privacy Policy**”) is intended to inform users of Status’ approach to privacy in respect of Status Software. In this regard, if you are using Status Software, this Privacy Policy applies to you.

Under the relevant data protection laws, we are under certain obligations if we process any personal data when you use Status Software. Personal data means all information by which a person can be directly or indirectly identified, in line with the definitions of the General Data Protection Regulation (GDPR), the Swiss Federal Act on Data Protection of June 19, 1992 (DPA) (as amended from time to time) and its ordinances, and other applicable law on the protection of personal data. When we refer to the relevant data protection laws in this Privacy Policy we mean GDPR, the DPA and any other applicable laws in this context.

This Privacy Policy describes, among other things, how we process the (limited) amount of personal data that we collect when you use Status Software. We also inform you about your rights and choices that you have in respect of any personal data we process.

If you do not agree with this Privacy Policy or any part of it, please do not use Status Software. If you are already using Status Software, we ask that you immediately stop using Status Software.

### 1) Who we are

Status is developing a set of open source projects that use peer-to-peer technologies to help people transact securely, communicate freely, and organise with confidence. Anyone participating in these projects helps to build technology and tools that empowers people to advance their own sovereign communities.

Whenever "Status" or "we" is used in this Privacy Policy, we're referring to Status Research & Development GmbH, a Swiss company with its registered offices at Baarerstrasse 10, 6302 Zug Switzerland. Our contact information can be found on our website and at the end of this Privacy Policy.

Status does not provide any services, such as financial services, to users of Status Software or any third party. Status is not an intermediary, agent, advisor, or custodian, and does not owe you any fiduciary duty.

### 2) Status Software

At Status, we strive to develop open source software that can serve as a secure communication tool that helps to uphold human rights. Status Software is specifically designed to facilitate the free flow of information, protect the right to private, secure communications and promote the sovereignty of individuals.

Status Software is composed of a secure messaging tool and a crypto wallet that are integrated together. Any software developed by Status in this regard is simply called “Status Software” and you can find more details about its development [here](https://status.app/).

### 3) Status processes personal data on a limited basis from your use of Status Software

Status processes personal data on a limited basis from users of Status Software and the specific types of personal data we process will depend on how you use Status Software. As such, we only collect and process personal data in the following instances:

1) **Usage Data:** Where you opt-in to share usage data, we collect and/or briefly process certain personal data about your interactions with Status Software. Adhering to the principle of privacy by design, this option is off by default. The situations where we collect usage data and the type of personal data we process are as follows:
    * *Network Behaviour*: Status Software utilises a private, censorship resistant, peer-to-peer messaging protocol called Waku ([https://waku.org/](https://waku.org/)). To allow us to understand the performance, usage patterns, and reliability of the Waku protocol, we collect non-personally identifiable information such as the number of messages sent to you, connected and discovered peers, the rate of successfully sent messages, type of connection to peers, and details about your OS, Status Software application version and bandwidth usage. Such usage data is linked to a randomly generated peer ID associated with your instance of Status Software, which is a unique identifier used for the duration of your interaction with Status Software and generated with each restart of the Status Software. While helpful for improving the protocol, it raises concerns about possible metadata exposure, such as the peer ID being used to track patterns. Such usage data will be kept for only as long as necessary to fulfil the aforementioned purposes and in any event, no longer than thirty (30) days and it will be deleted thereafter.
    * *Analytics*: Status also uses privacy-focused analytics to collect trends and insights about Status Software users. The usage data consists of personal data which we briefly process, that includes your IP address, universally unique identifiers of your device (UUID), and logs of actions, including button presses and screen visits, during your interactions with Status Software. Such usage data will be kept for only as long as necessary to fulfil the aforementioned purposes and it will be deleted thereafter.

    We process any personal data collected in the context of usage data based on your consent when you choose to opt-in. If you no longer wish to provide us any further usage data, you can opt-out at any time by disabling these functions.

2) **API Proxy Server**: When you use Status Software and specifically, the crypto wallet feature, Status Software will automatically interact with a server (“**API** **Proxy Server**”) that we control and has been implemented to improve the performance and security of Status Software and acts as a critical intermediary between a user’s instance of Status Software and a select number of third party service providers.

   The API Proxy Server is hosted on a number of reputable third party cloud providers (see section 4 of this Privacy Policy).

   As part of the implementation of the API Proxy Server, certain information, including personal data, from the user’s instance of Status Software, will be processed by Status through the API Proxy Server, which include the following:

    * *the user’s IP address*: your IP address will be processed by Status when third party requests are run through the API Proxy Server. This however removes your individual device details and IP address when the API Proxy Server makes the external requests to the third party service provider. As a result, these third-party service providers will only see the IP address of the API proxy server, not your IP address. The API Proxy Server receives your IP address whenever your instance of Status Software makes a https API call in the context of interacting with the following third party service providers:
        * Cryptocompare;
        * Infura;
        * Grove; or
        * Nodefleet.
    * *the user’s public address (also known as a wallet address)*: when you conduct certain activities on Status Software involving your Wallet (e.g. transactions conducted by the user), your public address is processed by Status in the API Proxy Server when making API calls to third party service providers, such as Grove or Infura. Your public address is shared by the API Proxy Server with Grove and Infura;
    * *Tokens a user might be interested in:* when you query the price data of tokens with Cryptocompare in Status Software, your instance of Status Software makes a https API call to the API Proxy Server as part of retrieving this information. Status will, through the API Proxy Server, process data that includes your query and the price data of the tokens that you queried for;
    * *Details of transactions entered into by the user*: when you enter into a transaction through Status Software, Status will process certain transaction information through the API Proxy Server. This includes the amounts and the sender and recipient(s) of the transaction, which contracts the user has interacted with and what functions are called in respect of those contracts. The details of the transaction are then shared by the API Proxy Server with Grove or Infura in order for the transaction to take place;
    * *Your data queries and response to this data query*: when you make a data query, such as an ERC-20 token balance call of a particular public address, this information is also processed by Status through the API Proxy Server. The details of these queries are shared by the API Proxy Server with Grove or Infura in order for the data query to be completed.

    Apart from your IP address, we do not retain any of the above personal data (or any other information) in line with the principle of data minimisation. The IP address will be kept for only as long as necessary to fulfil the aforementioned purposes and in any event, no longer than fourteen (14) days and it will be deleted thereafter.

    We process the above personal data for the purposes of facilitating the technical operation of Status Software and optimising the functionality and user’s experience of Status Software. We have a legitimate interest in processing this personal data for these purposes.

3) **Error Logs in Status Software**: To help troubleshoot issues, you can decide to enable logs, which will be stored locally on your device. When enabled, you are then able to subsequently share these logs with Status, which contains certain technical usage information, including details about your actions performed in Status Software. We note that such logs might also contain personal data. Status cannot collect these logs unless you share them with us. If you share these logs with Status, we process other personal data, such as a unique ID of the user's instance of Status Software, your IP address, and, depending how the logs are shared with Status, either your email address or Github username.

   This technical information helps us diagnose and resolve any technical problems efficiently. Such information will be kept for only as long as necessary to fulfil the aforementioned purposes and in any event, no longer than thirty (30) days and it will be deleted thereafter

### 4) Personal data sharing with third party service providers

We share personal data with third party service providers in the context of fulfilling the above purposes in which we collect and process personal data. We have contracted such third party service providers to provide their services and act as data processors on our behalf and they are only permitted to process personal data in accordance with our instructions.

Third party service providers we engage and services we utilise from them include:

* *DigitalOcean*: Providing hosting services in relation to the API Proxy Server;
* *Alibaba Cloud*: Providing hosting services in relation to the API Proxy Server;
* *Google Cloud*: Providing hosting services in relation to the API Proxy Server;and
* *Cryptocompare*: Providing data and information services around cryptocurrency prices;
* *Infura*: Providing RPC services;
* *Grove*: Providing RPC services;
* *Nodefleet*: Providing RPC services;
* *MixPanel*: Providing analytics services in relation to the Usage Data.

### 5) Third party collection and processing of personal data

In addition to our limited collection of personal data, third parties themselves might collect or process personal data as a result of Status Software making use of certain features, to provide certain content or making available to the user certain services as provided by third parties. For the avoidance of doubt, Status does not collect or process this personal data. To the extent you interact with such third party content or features, their respective privacy policies will apply.

We also note the following:

* *Cookies*: We do not set any cookies for the use of Status Software. However, the Web 3 browser embedded within Status Software technically supports the use of cookies set by third party websites. Status is not responsible for nor is it able to influence whether such cookies are set by such third party websites and you should consult the relevant privacy policies of such third party websites.
* *Web 3*: An inherent feature of Web 3 is its transparency, particularly in the context of blockchain networks. This means that your public key and wallet address will be visible to others when you engage in transactions on such networks and that third parties may be able to (and for the avoidance of doubt, not through the use of Status Software) connect your public key and wallet address to your identity and determine the Digital Assets you own in your Wallet. You should also be aware that entries on blockchain networks are practically immutable, which means that they generally cannot be deleted or modified by anyone, including Status, even if the transaction turns out to have been made in error or otherwise.
* *Other third party service providers*: Status Software allows you to interact with a number of third party service providers, including on-ramp providers, cryptocurrency price service providers, NFT collectible service providers, swap providers and signature tooling providers. These providers might collect and process your personal data if you use their services. Please consult the relevant privacy policy of these third party service providers prior to your use of their services.

### 6) Security measures we take in respect of Status Software

As a general approach, Status takes data security seriously and the measures we take as an organisation. In respect of Status Software, we implement a variety of security measures that are reasonably designed to maintain the safety of your personal data when it is shared with us.

### 7) Exporting personal data outside the European Union and Switzerland

While it is not intended that Status will export your personal data outside the European Union or Switzerland, Status is obliged to protect the privacy of such personal data if it is exported outside these areas and it will only be processed in countries or by parties that provide an adequate level of protection as deemed by Switzerland or the European Commission. Otherwise, Status will use specific forms of contractual clauses to ensure such personal data is provided the same protection as required in Switzerland or Europe. The transmission of personal data outside the European Union and Switzerland will always occur in conformity with applicable data protection laws.

### 8) Your choices and rights

As explained in this Privacy Policy, Status limits its collection and processing of your personal data. Nonetheless, you still have certain choices and rights in respect of the personal data which we do collect and process. As laid out in relevant applicable data protection laws, you have the right to:

* Ask us to correct or update your personal data (where possible);
* Ask us to remove your personal data from our systems;
* Ask us for a copy of your personal data, which may also be transferred to another data controller at your request;
* Withdraw your consent to process your personal data (only if consent was asked for a processing activity), which only affects processing activities that are based on your consent and doesn't affect the validity of such processing activities before you have withdrawn your consent;
* Object to the processing of your personal data; and
* File a complaint with the Federal Data Protection and Information Commissioner (FDPIC), if you believe that your personal data has been processed unlawfully.

Once we receive your request, we might require you to verify your identity such that we can appropriately respond to your request and we will do so in line with any applicable mandatory deadlines. Please contact us with the relevant request at: [legal@status.im](mailto:legal@status.im).

### 9) Third party websites

Within Status Software, you might come across links to third party websites. These third party sites will often have separate and independent privacy policies. We therefore have no responsibility or liability for the content and activities of these linked sites. Please refer to these privacy policies of these third party websites when you use such websites.

### 10) The Privacy Policy might change

We may modify or replace any part of this Privacy Policy. Please check on Status Software periodically for any changes. The new Privacy Policy will be effective immediately upon it being placed in Status Software .

### 11) Contact Information

To the extent that you have any questions about the Privacy Policy, please email us at [legal@status.im](mailto:legal@status.im).

This document is licensed under CC-BY-SA.
