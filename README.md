# CP-MNER: A Chinese Painting Multimodal Named Entity Recognition Dataset

CP-MNER is a multimodal named entity recognition (MNER) dataset for the Chinese painting domain. It is designed to support fine-grained entity extraction from paired **painting images** and **descriptive texts**, and to provide a standardized benchmark for multimodal information extraction in cultural heritage scenarios.

The dataset was introduced in the following paper:

> Wan, J., Chen, S., Zeng, Q. et al. **A multi-path fusion with knowledge augmentation framework for multimodal NER in Chinese painting**. *npj Heritage Science* **14**, 265 (2026).

---

## Overview

Chinese painting descriptions often contain rich historical, artistic, and cultural information, but this information is usually embedded in long unstructured text and closely related to visual content. To facilitate research on multimodal named entity recognition in this domain, we construct **CP-MNER**, a Chinese painting MNER dataset with fine-grained domain-specific entity annotations.

CP-MNER can be used for tasks such as:

- multimodal named entity recognition
- cross-modal semantic understanding
- cultural heritage knowledge extraction
- fine-grained entity analysis in art descriptions

---

## Dataset Characteristics

- **Domain**: Chinese painting
- **Task**: Multimodal Named Entity Recognition (MNER)
- **Data format**: image-text pairs with sequence labeling annotations
- **Total samples**: 1,188 image-text pairs
- **Entity types**: 16 domain-specific categories
- **Annotation scheme**: BIO2
- **Annotation granularity**: Chinese character level

---

## Entity Types

CP-MNER contains the following 16 entity types:

| Entity Type | Description | Example |
|---|---|---|
| ARTWORK | Artwork titles, painting names, classical painting subjects | *Along the River During the Qingming Festival* |
| TECHNIQUE | Painting techniques, brushwork, ink techniques | gongbi, xieyi, boneless technique |
| LOCATION | Real geographic locations, place names, sites | China, Zhejiang, Hangzhou |
| PERSON | Real person names, painters, historical figures | Qianlong, Kangxi, Li Qingzhao |
| ARCHITECTURE | Buildings, bridges, pavilions, palaces | temple, palace, garden |
| LANDSCAPE | Natural scenery, mountains, rivers, terrain elements | mountain, water, cloud, mist |
| SEAL | Seals, seal inscriptions, colophons | “Qianlong Yulan Zhibao”, “Qianlong Baoxi” |
| SIZE | Artwork dimensions, width/height measurements | “99.3 cm in height”, “61.9 cm in width” |
| MATERIAL | Painting materials, paper, silk, media | xuan paper, silk |
| PLANT | Flowers, trees, grasses, plant species | plum blossom, orchid, chrysanthemum |
| FIGURE | Human or character figures depicted in the painting, including deities and fictional figures | Guanyin, Tathagata |
| OBJECT | Utensils, tools, decorative objects | vase, tea set, porcelain |
| STYLE | Artistic styles and schools | Wu School, Four Wangs |
| TIME | Dynasties, historical periods, dates | Qing dynasty, Ming dynasty, Song dynasty |
| ORGANIZATION | Institutions, museums, organizations | Palace Museum, National Museum of China |
| ANIMAL | Animals, birds, mythical creatures | lion, tiger, dragon |

