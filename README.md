# foodstyles_challenge
Contains notebooks for data processing & training, and inference

# Screenshots
- [Training](https://vimeo.com/553608418/be4bb421ec)
- [Inference](https://vimeo.com/553638394/0e51a87e79)

# Note
For the output, I slightly modified the expected return to this:

```json
{'recipe_2': {'vanilla': [(118, 125)],
  'coffee': [(106, 112)],
  'baking': [(176, 182)],
  'margarine': [(64, 73)],
  'sugar': [(75, 80)],
  'butter': [(54, 60)],
  'egg': [(82, 85)],
  'flour': [(163, 168), (223, 228)],
  'salt': [(170, 174)],
  'powder': [(183, 189)],
  'banana': [(88, 94)],
  'soda': [(195, 199)],
  'chocolate': [(245, 254)]},
 'recipe_1': {'vanilla': [(207, 214)],
  'ground': [(163, 169)],
  'baking': [(180, 186)],
  'vegetable': [(105, 114)],
  'cinnamon': [(170, 178)],
  'sugar': [(149, 154)],
  'soda': [(188, 192)],
  'flour': [(66, 71), (156, 161)],
  'salt': [(194, 198)],
  'apples': [(247, 253)],
  'cake': [(86, 90), (355, 359), (383, 387)],
  'oil': [(115, 118)],
  'eggs': [(123, 127)]
```
This modification is to easily see the model's predicted ingredients
