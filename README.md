# Cedille AI

**[📝 Try out Cedille in our playground!](https://app.cedille.ai/)**

## 📦 Open AI

### HuggingFace

[Cedille is available on 🤗HuggingFace](https://huggingface.co/Cedille/fr-boris)

This is the most convenient way to use the model for most people.

### Mesh Transformer

Model checkpoint: [French model, 150k training steps ("Boris")](https://storage.googleapis.com/cedille-public/models/boris/step_150000.tar.gz) (9.0gb tar file!)

Cedille is a GPT-J model, it can be run using the [`mesh-transformer-jax` codebase](https://github.com/kingoflolz/mesh-transformer-jax).

### Why is this repository empty?

The Cedille model is open-source:
- The model checkpoints are provided above (MIT License)
- It was trained using the [`mesh-transformer-jax` codebase](https://github.com/kingoflolz/mesh-transformer-jax) (Apache-2.0 License)
- It can be run either using the [🤗Transformers library](https://github.com/huggingface/transformers) (Apache-2.0 License) or [`mesh-transformer-jax`](https://github.com/kingoflolz/mesh-transformer-jax) depending on your needs

And that's all there is to it! This repository is mostly here to guide you towards these resources 😉

## 📊 Cedille paper

Our paper is out now! https://arxiv.org/abs/2202.03371

Thanks for citing our work if you make use of Cedille
```bibtex
@misc{muller2022cedille,
      title={Cedille: A large autoregressive French language model}, 
      author={Martin M{\"{u}}ller and Florian Laurent},
      year={2022},
      eprint={2202.03371},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```

## 🔗 Links

Website: https://cedille.ai

Playground: https://app.cedille.ai/

Twitter: https://twitter.com/cedilleai

Paper: https://arxiv.org/abs/2202.03371

## 🙏 Acknowledgement

* The project was made possible with the generous support from the [Google TRC program](https://sites.research.google/trc/about/).
* Cedille is based on the [GPT-J model](https://github.com/kingoflolz/mesh-transformer-jax) developed by [EleutherAI's wizards](https://www.eleuther.ai/).
