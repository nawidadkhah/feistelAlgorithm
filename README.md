# Feistel algorithm
This is a Feistel algorithm but it is not a classic one, it contains some changes.
The main process of the algorithm in one round is as below:

<p align="center">
  <img src="https://github.com/nawidadkhah/feistelAlgorithm/assets/79360286/8fb158ee-63a1-4964-aad7-867ad0292289">
</p>

# F function 
This function is used for change parts of the string with math operations and help the right part of the string.
Tables help us to change the length of the string.

# New generating sub-keys
In the algorithm, we change how to create sub-keys. we replace it with the s-box table. in each iteration, we create a specific sub-key that inspired by the previous one 
and the first sub-key, permutation duo to the original key.
