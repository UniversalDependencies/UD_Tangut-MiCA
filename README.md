# Summary

Tangut Treebank (𗼇𘝞𘕰𗾊, MiCA) is an annotated treebank of Tangut texts, developed by the Mi (𗼇) Corpus Annotation Group.

# Introduction

This treebank is based on the Tangut versions of chapters from two sūtras. Texts are transcribed from published images of manuscripts and annotated.

Tangut manuscripts generally contain no punctuation between words or sentences. For UD annotation, word segmentation and punctuation are added. The treebank provides lemmas, universal part-of-speech tags, morphological features, dependency relations, and lexical glosses and transliterations in `MISC`.

The current release contains one file:

* `txg_mica-ud-test.conllu`
    - Chapter 25 of the *Lotus Sūtra* (法華經), based on the manuscript images published by Chen Bingying (1985).
    - Volume 77 of the *Avataṃsaka Sūtra* (華嚴經), based on the manuscript images published by Arakawa Shintarō (2011).

The two source texts can be distinguished by the prefixes `lotus_sutra_` and `avatamsaka_sutra_`. 

# Acknowledgments

We thank Tak Wai Wong for permission to use his earlier [Universal Dependencies annotations of the Tangut Lotus Sutra](https://twwspes.github.io/annodoc/saddharmapundarika_sutra/24_tangut).

We thank Xun Gong for permission to use his work on Tangut [pronunciation](https://github.com/semakosa/tangut-pronunciation-db) and glossary (Reichert Verlag, forthcoming), subject to its own Limited Public Use License.

The English translation of the *Lotus Sutra* is taken from [500 Yojanas](https://www.500yojanas.org/lotus-sutra/), under CC BY. The English translation of the *Avataṃsaka Sūtra* is based on Bhikshu Dharmamitra, [*The Flower Adornment Sutra*](https://kalavinka.org/#A_Complete_Translation_of_the_Avatam%CC%A3saka_Sutra) (Kalavinka Press, 2022), with kind permission for partial use. We thank them.

Lexical glosses refer in part to [TangutTranslator](https://github.com/C27Ezx/TangutTranslator/blob/main/tangut_learning_data.json), based on Alan Downes's [Tangut.info](https://tangut.info/). We thank them.

## References

* Chen, Bingying (陈炳应). 1985. “An Annotated Translation of the Illustrated Tangut *Guanyin Sutra*” (图解本西夏文〈观音经〉译释). *Dunhuang Research* (敦煌研究), no. 3, pp. 49–58.
* Arakawa, Shintaro (荒川慎太郎). 2011. “[An Annotated Japanese Translation of the Tangut Version of *Avataṃsaka Sūtra*, Vol. 77 in Princeton University Collection](https://tufs.repo.nii.ac.jp/record/2077/files/jaas081006_ful.pdf)” (プリンストン大学所蔵西夏文華厳経巻七十七訳注). *Journal of Asian and African Studies* (アジア・アフリカ言語文化研究), vol. 81, pp. 147–305.
* Hua, Wenjie; Lin, Chia-Wei; Zheng, Yuxi; Ji, Yue; Zhang, Longyu; Jiang, Zhengshi; Zeldes, Amir. 2026. “[UD-Tangut-MiCA](https://github.com/UniversalDependencies/UD_Tangut-MiCA).” Universal Dependencies treebank, GitHub repository.


# Changelog

* 2026-11-15 v2.19
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.19
License: CC BY-SA 4.0
Includes text: yes
Parallel: no
Genre: narration poetry
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Hua, Wenjie; Lin, Chia-Wei; Zheng, Yuxi; Ji, Yue; Zhang, Longyu; Jiang, Zhengshi; Zeldes, Amir
Contributing: here
Contact: wh583@georgetown.edu
===============================================================================
</pre>
