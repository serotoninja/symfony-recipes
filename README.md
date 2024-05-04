<div align="center">

# Symfony Recipes
Welcome to my tiny, shiny Symfony Flex recipe repository!

[![symfony/recipes](https://img.shields.io/badge/symfony-recipes-374151.svg?style=flat-square)](https://github.com/symfony/recipes)
[![symfony/recipes-contrib](https://img.shields.io/badge/symfony-recipes--contrib-374151.svg?style=flat-square)](https://github.com/symfony/recipes-contrib)

[![php](https://img.shields.io/badge/PHP->=8.0-4F5B93.svg?style=flat-square)](https://www.php.net)
[![composer](https://img.shields.io/badge/composer-^2.1-D48822.svg?style=flat-square)](https://getcomposer.org)
[![symfony](https://img.shields.io/badge/symfony/flex-^2-374151.svg?style=flat-square)](https://github.com/symfony/flex)

</div>

---

## Getting Started
This repository contains custom Symfony Flex recipes tailored for my Symfony bundles and packages. 
To enable recipes defined in this repository for your project, add this endpoint in your project's `composer.json` as described in the 
[Symfony documentation](https://symfony.com/doc/current/setup/flex_private_recipes.html#configure-your-project-s-composer-json-file):
```json
{
    "extra": {
        "symfony": {
            "endpoint": [
                "https://api.github.com/repos/serotoninja/symfony-recipes/contents/index.json",
                "flex://defaults"
            ]
        }
    }
}
```

> [!WARNING]
> Without this option Composer will not use the Symfony Flex recipes for my bundles, unless the recipes were contributed to
> [symfony/recipes-contrib](https://github.com/symfony/recipes-contrib). Then you will need to follow manual installation
> instructions, if provided. 

> [!NOTE]  
> See [RECIPES.md](https://github.com/serotoninja/symfony-recipes/blob/flex/main/RECIPES.md) for a full list of recipes that live in this repository.

## Contributing
Contributions to this repository are restricted to authorized team members. If you have a recipe to contribute, 
please contact the repository owner for access.

## Support
If you encounter any issues or have questions about using our recipes, please contact our support team.

## License
This repository is private and for internal use only. Unauthorized distribution or use of its contents is prohibited.

## About me
I am a developer dedicated to creating high-quality Symfony applications. Feel free to reach out to us with any 
inquiries or collaboration opportunities.

## Acknowledgements
I would like to thank the Symfony community for their valuable contributions to the ecosystem.
