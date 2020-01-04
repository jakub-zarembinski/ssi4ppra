#### A. Proces "emitent-PPRA": wygenerowanie identyfikatora emitenta i przekazanie go PPRA

1. Emitent generuje unikalny DID oraz parę kluczy (prywatny i publiczny)

2. Emitent rejestruje na blockchainie swój DID oraz powiązany z nim klucz publiczny

3. Emitent przesyła swój DID do PPRA

#### B. Proces "akcjonariusz-emitent": wygenerowanie przez emitenta certyfikatu potwierdzającego tożsamość akcjonariusza i przekazanie go akcjonariuszowi

4. Akcjonariusz generuje unikalny DID oraz parę kluczy (prywatny i publiczny)

5. Akcjonariusz przesyła swój DID do emitenta

6. Emitent identyfikuje akcjonariusza i przekazuje mu podpisany cyfrowo VC łączący DID akcjonariusza z jego danymi identyfikacyjnymi

#### C. Proces "akcjonariusz-PPRA": identyfikacja akcjonariusza przez PPRA i realizacja jego polecenia

7. Akcjonariusz przekazuje VC do PPRA i udowadnia kontrolę nad DIDem którego dotyczy ten VC

8. PPRA weryfikuje VC upewniając się że został on podpisany kluczem przyporządkowanym do DIDa emitenta

9. PPRA identyfikuje akcjonariusza na podstawie informacji zawartych w VC

10. PPRA realizuje polecenie akcjonariusza
