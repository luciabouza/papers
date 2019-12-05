# NLP papers, tl;dr

## Adversarial Examples

* (2017) R.Jia and P. Liang: [Adversarial Examples for Evaluating Reading Comprehension Systems](https://arxiv.org/abs/1707.07328) 
- **TLDR**: A partir del corpus SQuAD (que incluye un p�rrafo de Wikipedia, una pregunta y sus respuesta), los autores crean ejemplos adversarios
agregando una oraci�n adversaria al p�rrafo (_concatenative adversaries_), que buscan confundir a la pregunta, porque son parecidas (pero no contradicen) a la pregunta y sugieren
una respuesta. Hacen caer el F1-score de 75% a 36%. Presentan tambi�n un m�todo independiente del modelo, que agrega una oraci�n aleatoria (pero con sentido) al p�rrafo.

### Otros repositorios

- [nlp-library](https://github.com/mihail911/nlp-library), by [Mihail Erik](https://github.com/mihail911)
