<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->




<!-- PROJECT LOGO -->
<br />
<div align="center">
  </a>

  <h3 align="center">The Generative AI Image Retargeting Experiment</h3>

  <p align="center">
    This experiment explores consistency in AI image generation through the use of prompt narrowing, prompt flooding, and prompt referencing by a four phase process.
    <br />
    Fall of the Mourning Star
    <br />
    <br />
    <br />
    <a href="https://britainthomas32.wixsite.com/portfolio/projects">Britain Thomas</a>
    &middot;
    <a href="https://sites.google.com/view/viza626/home">VIZA 626</a>
  </p>
</div>

[![4-comma][images-fig1]](https://example.com)

Figure 1. Fall of the Mourning Star, Is a Yonkoma representing the birth and death of a star through the narrative of a poem combined visually with AI Generated Images sourced from OpenAI's DALL-E 3.

<!-- Abstract -->
## Abstract

The Generative AI Image Retargeting Experiment focused on applying the concept of prompt narrowing, prompt flooding, and prompt referencing. By applying these concepts when generating artwork, proved a consistency between panels: Previous tests without applying the concepts proved to be less consistent. The goal of combining these approaches was to further consistency between multi panel AI generated artwork. Through the use of prompt referencing specifically, the framing of characters before generation proved significantly more consistent than only using prompt narrowing and prompt flooding. Applying these concepts to generate artwork, the results of the experiment proved more consistent than originally anticipated.

[![4-comma][images-fig2]](https://example.com)

Figure 2. The Experiment Workflow to generate the consistency comic through the use of the four phases of the experiment prompt narrowing, prompt flooding, prompt referencing to then be assembled in the the finalization process seen in phase four.

<!-- Introduction and Related Works -->
## Introduction and Related Works

In the pursuit of more consistent artwork, the concepts of applying prompt narrowing, prompt flooding, and prompt referencing developed over time through the desire for more consistent, yet complex, characters between generated artwork in the OpenAI’s Dall-E 3.0 generation model. OpenAI’s image generation model has the unique opportunity of applying all three concepts that is otherwise unseen in other models that require better illusion mitigation features: By Dall-E being packaged with ChatGPT, the model has potential for consistency than other models through the use of these concepts. Tests of Dall-E’s accuracy have proven to be difficult according to evaluating realistic medical images [1]; therefore, demand for more image consistency is necessary for improving the model’s accuracy. Previous studies have been conducted to improve prompt curation for other diffusion models, like stable diffusion, and have proven to improve image quality [2]. The inclusion of ChatGPT with Dall-E gives opportunity to further develop prompt curation with prompt referencing being the forefront of prompt optimization. The application of prompt referencing has proven to be more efficient in other studies in Dall-E 2.0 [3]. By incorporating all of these methods of image generation consistency, this experiment proved to generate more consistent images.

[![4-comma][images-fig3]](https://example.com)

Figure 3. The Experiment Pipeline used to generate the comic's consistency for each of the 10 panels showcasing the steps of the entire experiment in a condensed view.

[![4-comma][images-fig4]](https://example.com)

Figure 4. The mathematics formula for prompt narrowing during Phase 1 of the experiment. Each initial prompts generated (p) are first narrowed down by color (c) and theme (t) then combined to generate images (G) based on the prompt (p) and referenced images (R). The the initial prompts are influenced by the narrative poem (P) to further direct the image generation consistency.

[![4-comma][images-fig5]](https://example.com)

Figure 5. The mathematics formula for prompt flooding during Phase 2 of the experiment. The best prompts (p*) are determined by the highest evaluation score (arg max) of the evaluated (E) generated images (G) when generated with the initial prompts (p). Where the initial prompts (p) are a series of iterated colors (c) and themes (t). Prompt Flooding (ph) is then enriched by the combination of all elements of prompts influence of the narrative poem (P).

[![4-comma][images-fig6]](https://example.com)

Figure 6. The mathematics formula for prompt referencing during Phase 3 of the experiment. Reference Images utilized (R) are generated by being influenced by the iterated images (I) of the set of colors (c) and set of themes (t) of the narrowed prompts. The final prompt references (I') are then enriched by the generated image function (G) of the flooded prompt (ph) combined with the reference images utilized (R).

[![4-comma][images-fig7]](https://example.com)

Figure 7. The mathematics formula for prompt referencing during Phase 4 of the experiment. Consistent image generation (Itop) is generated by the Top 10 iterations (T) influenced by the final prompt references (I') then the final comic (F) is assembled based on the top images generated (Itop).

## Methodology

The steps of this experiment were broken down into four major phases that were recursively built on top of each other to generate the 10 panel comic, figure 1, seen in the workflow overview displayed in figure 2. The pipeline workflow, figure 3, displays the steps to generate each comic panel, and the process of image generation to achieve consistency between each individual panel. Phase One of the experiment was the initial database building stage of the project that utilized prompt narrowing to initially generate the images along with the minor prompts for establishing a base model of the desired color and desired theme of the comic. The mathematics formula of Phase One showcases the building process, figure 4, of how every iteration’s impact on influencing the initial results, and how each iteration narrows the prompts for optimization purposes. Phase Two of the experiment applied the initial steps in Phase One to generate the prompt flooding technique, of taking optimized prompts and making ChatGPT prioritize hyper specificity of the prompts for more consistent prompt generation, showcased in figure 8. The formula of this process is displayed in figure 5 on the process of maximizing the capability of each prompt. Phase Three of the experiment showcased the combination of previous phases with the combined effort of prompt referencing for consistent and desirable images. Phase Three’s formula is showcased in figure 6 in the unification of the iterated image sets combined with the prompt references through the hyper-specific prompt generated during Phase Two’s prompt flooding methodology. Phase Four of the experiment was the final summation of all phases in the curative process of assembling the comic, and the mathematics applied in this assembly process is displayed in figure 7. The poem provided the assembly process the desired narrative seen in figure 1.

[![4-comma][images-fig8]](https://example.com)

Figure 8. The Prompt Referencing Image Consistency Diagram showcase each iterations consistency ranking based on Color, Theme, Composition, Aesthetic, and visual Balance when Prompt Referencing is applied in isolation.

## Result and Future Work

The outcome of the experiment proved to generate more consistency when all three concepts were utilized, and the accuracy of the images generated proved to be satisfactory. Previous experiments that utilized prompt narrowing only, showed a dramatic improvement in the amount of iterations required to generate each of the panels when applying the method used within this experiment. The vision originally set for this experiment was proven that the Dall-E 3.0 model is capable of consistency and accuracy when prompts are optimized with the right framework, seen in figure 3 when tested for consistency. The combination of the concepts of prompt narrowing, prompt flooding, and prompt referencing provided less illusions overall than previous tests when individual phases were tested in isolation. Potential room for improvement within the experimentation process is expanding the library of desirable images with a target goal of providing Dall-E the framework of user specific definitions. For instance, the use of user-specific prompt framing by training Dall-E to identify simple user defined features, such as what an outline or stroke on a subject means, by expanding Phase One with Phase Three’s prompt referencing to narrow prompts via images, the iteration framework being showcased in figure 9.

[![4-comma][images-fig9]](https://example.com)

Figure 9. The Prompt Referencing Pipeline used to generate the main character when combined with all the previous phases.

## Conclusion
The overall experiment provided an insight in image generation by reverse engineering prompt optimization. Prompt referencing specifically proved to be significant in consistency of complex generation. Future experiments will further prioritize how to expand prompt referencing, and where to include primarily image-based prompts: Shifting from text-to-image prompts to the model of image-to-image based prompts. Figure 10 showcasing the framework building process through the image-to-image prompt utilization. The incorporation of a user-defined prompt framework was a minor addition to this experiment in Phase Four, but the inclusion was so vital to image consistency that future experiments will be following this methodology.

[![4-comma][images-fig10]](https://example.com)

Figure 10. The showcase of future expansion to the experiment with User-Generated User-Specific prompts defined by the users input on what the user's prompt means associated with their desired image example.

<!-- Bibliography -->
## Bibliography 
[1] Temsah, M. H., Alhuzaimi, A. N., Almansour, M., Aljamaan, F., Alhasan, K., Batarfi, M. A., ... & Nazer, R. (2024). 
Art or artifact: evaluating the accuracy, appeal, and educational value of AI-generated imagery in DALL· E 3 for 
illustrating congenital heart diseases. Journal of Medical Systems, 48(1), 54.


[2] Mo, W., Zhang, T., Bai, Y., Su, B., Wen, J. R., & Yang, Q. (2024). Dynamic prompt optimizing for text-to-image 
generation. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (pp. 26627-26636).


[3] Fan, Z., Li, X., Nag, K., Fang, C., Biswas, T., Xu, J., & Achan, K. (2024, May). Prompt optimizer of text-to-image 
diffusion models for abstract concept understanding. In Companion Proceedings of the ACM Web Conference 2024 (pp. 1530-1537).



<!-- CONTACT -->
## Contact

Britain Thomas - britainthomas@tamu.edu

Personal Website: https://britainthomas32.wixsite.com/portfolio/projects




<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

This work is submitted as part of Assignment 2 for the VIZA 626 course at Texas A&M University, under the instruction of Professor You-Jin Kim, during the Spring 2025 semester.

VIZA 626 Class Website: [https://sites.google.com/view/viza626/](https://sites.google.com/view/viza626/home)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[images-fig1]: images/fig1.png
[images-fig2]: images/fig2.png
[images-fig3]: images/fig3.png
[images-fig4]: images/fig4.png
[images-fig5]: images/fig5.png
[images-fig6]: images/fig6.png
[images-fig7]: images/fig7.png
[images-fig8]: images/fig8.png
[images-fig9]: images/fig9.png
[images-fig10]: images/fig10.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
