### Question 1

   - Question :
      ```c++
         vector<int> v(2, 1);
         v.resize(4, 2);
         v.pop_back();
      ```
   - Consigne:
    ```
        Ecrire les valeurs de v avec un seul espace entre les valeurs.
    ```
    
   - Réponse :
      ```
         1 1 2
      ```
   
### Question 2

   - Question :
      ```c++
         vector<int> v{ 1, 2, 3, 4, 5 };
         v.insert(v.end() - 2, 2, 1);
      ```
   - Consigne:
    ```
        Ecrire les valeurs de v avec un seul espace entre les valeurs.
    ```
    
   - Réponse :
      ```
         1 2 3 1 1 4 5
      ```

### Question 3

   - Question :
      ```c++
         vector<int> v{ 1, 2, 3, 4, 5 };
         v.erase(v.begin() + 2, v.end() - 2);
         v.resize(5, 2);
      ```
   - Consigne:
    ```
        Ecrire les valeurs de v avec un seul espace entre les valeurs.
    ```
    
   - Réponse :
      ```
         1 2 4 5 2
      ```
   
### Question 4

   - Question :
      ```c++
         vector<int> temp{ 1, 2, 3, 4, 5 };
         vector<int> v(temp.begin() + 1, temp.begin() + 3);
      ```
   - Consigne:
    ```
        Ecrire les valeurs de v avec un seul espace entre les valeurs
    ```
    
   - Réponse :
      ```
         2 3
      ```

### Question 5

   - Question :
      ```c++
         vector<int> v{ 1, 2, 3, 4 };
         for (auto i = v.rbegin() + 1 ; i != v.rend() - 1; i++) {
            (*i)++ ;
         }
      ```
   - Consigne:
    ```
        Ecrire les valeurs de v avec un seul espace entre les valeurs.
    ```
    
   - Réponse :
   ```
      1 3 4 4
   ```

### Question 6

   - Question :
      ```c++
         vector<int> v{ 1, 2, 3 };
         for (int i : v) {
            i++;
         }
      ```
   - Consigne:
    ```
        Ecrire les valeurs de v avec un seul espace entre les valeurs.
    ```
    
   - Réponse :
      ```
         1 2 3 
      ```

### Question 7

   - Question :
      ```c++
         void fct(vector<int> v1, vector<int>v2) {
            v1 = v2;
         }
         vector<int> temp{ 1, 2, 3 };
         vector<int> v(4, 1);
         fct(v, temp);
      ```
   - Consigne:
    ```
        Ecrire les valeurs de v avec un seul espace entre les valeurs.
    ```
    
   - Réponse :
      ```
         1 1 1 1
      ```

### Question 8

   - Question :
      ```c++
         vector<int> &  fc(vector<int> & a) {
            return a;
         }
         vector<int> temp{ 1, 2, 3 };
         vector<int> v(5, 1);
         fc(v) = temp;
      ```
   - Consigne:
    ```
        Ecrire les valeurs de v avec un seul espace entre les valeurs.
    ```
    
   - Réponse :
      ```
         1 2 3
      ```
