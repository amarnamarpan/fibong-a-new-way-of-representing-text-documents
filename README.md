# fibong-a-new-way-of-representing-text-documents

The module allows a simple import and use functionality to extract the fibong representation from any given text. 
The sample syntax of using it as shown below.
```python
import fibong as fb
text = '''
A gnarble left his cozy bed along the ocean floor. He dreamt about a place that he had never seen before! He headed to the surface for a glimpse of sun and sky. A trip so long and perilous, he'd be the first to try!
'''
fibong_terms = fb.get_fibong_terms(text)
print(fibong_terms)
```
Output:
```
['gnarble', 'left', 'cozy', 'bed', 'ocean', 'floor', 'dreamt', 'place', 'never', 'seen', 'headed', 'surface', 'glimpse', 'sun', 'sky', 'trip', 'long', 'perilous', "he'd", 'first', 'try', 'gnarble left', 'cozy bed', 'ocean floor', 'floor He', 'He dreamt', 'never seen', 'He headed', "perilous he'd", 'ocean floor He', 'glimpse of sun', 'trip so long', 'long and perilous']
```
