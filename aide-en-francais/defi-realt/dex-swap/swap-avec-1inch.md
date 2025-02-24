# Swap avec 1inch

Comment, étape par étape, faire un échange en P2P (achat/vente/échange) de RealToken avec l'application [1Inch](https://app.1inch.io/) :&#x20;

<figure><img src="../../../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>

1. Vous vous connectez à l'application et sélectionnez la chain Gnosis,
2. Sélectionner l'onglet 2P2 dans l'app,
3. Entrer l'adresse du Realtoken que vous souhaitez échanger (ici c'est une vente),
4. Indiquer le nombre de RealToken que vous souhaitez échanger (ici 0,1),
5. Indiquer la monnaie d'échange (ici USDC),
6. Indiquer le montant que vous souhaitez en échange (ici 5, USDC pour 0,1 RealToken),
7. L'application donne le prix par Token (ici 50 USDC / RealToken),
8. Indiquer l'adresse du wallet avec qui vous souhaitez échanger (qui devra avoir été [whitelisté](../../site-realt/procedure-de-whitelisting.md) pour ce RealToken, sinon la transaction va échouer),
9. Indiquer la durée de validité de votre offre (ici 10 mn).

Vous allez ensuite : signer l'autorisation d'accès du contrat 1inch à votre RealToken, puis autoriser la création de l'ordre d'échange.

L'application vous donnera alors la référence de l'offre d'échange à transmettre :&#x20;

<figure><img src="../../../.gitbook/assets/image (101).png" alt=""><figcaption></figcaption></figure>

Avec cette référence, le wallet destinataire de l'échange, va pouvoir accéder à l'offre, signer l'autorisation d'accès au token d'échange (ici USDC), puis autoriser l'échange :&#x20;

<figure><img src="../../../.gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>
