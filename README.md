# Introduction to PHP 8

- **Place**: [Omedia](https://omedia.dev/)
- **Time**: 19/11/2020 17:00 (GMT+4) 
- **Speaker**: [Temuri Takalandze](https://abgeo.dev/)
- **Watch**: https://youtu.be/opzZZ4opp4g

## Content

- [General](code/1_general) (slides 4-21)
    - JIT (slides 5-12)
        - How PHP works (slides 6-7)
        - OPcache (slides 8-9)
        - Preloading (slide 10)
        - JIT Compiler (slides 11-12)
    - [Attributes](code/1_general/2_attributes.php) (slide 13)
    - [Named arguments](code/1_general/3_named_arguments.php) (slide 14)
    - [The nullsafe operator](code/1_general/4_nullsafe_operator.php) (slide 15)
    - [Match expression](code/1_general/5_match_expression.php) (slide 16)
    - [Throw expression](code/1_general/6_throw_expression.php) (slide 17)
    - [Non-capturing catches](code/1_general/7_non_capturing_catches.php) (slide 19)
    - [Trailing comma in parameter lists](code/1_general/8_trailing_comma.php) (slide 19)
    - [Concatenation precedence](code/1_general/9_concatenation_precedence.php) (slide 20)
    - `ext-json` always available (slide 21)
- [About types](code/2_types) (slides 22-26)
    - [Union types](code/2_types/1_union_types.php) (slide 23)
    - [`mixed` type](code/2_types/2_mixed_return_type.php) (slide 24)
    - [`static` return type](code/2_types/3_static_return_type.php) (slide 25)
    - [New `Stringable` interface](code/2_types/4_stringable_interface.php) (slide 26)
- [What’s new in OOP?](code/3_oop) (slides 27-33)
    - [Constructor property promotion](code/3_oop/1_constructor_property_promotion.php) (slide 28)
    - [Inheritance with private methods](code/3_oop/2_inheritance_with_private_methods.php) (slide 29)
    - [Allowing `::class` on objects](code/3_oop/3_allowing_class_on_objects.php) (slide 30)
    - [Abstract trait method validation](code/3_oop/4_abstract_trait_method_validation.php) (slide 31)
    - [Weak maps](code/3_oop/5_weak_maps.php) (slide 32)
    - [Token as object](code/3_oop/6_token_as_object.php) (slide 33)
- [New built-in functions](code/4_functions) (slides 34-39)
    - [`str_contains()`](code/4_functions/1_str_contains.php) (slide 35)
    - [`str_starts_with()` & `str_ends_with()`](code/4_functions/2_str_starts_with_and_str_ends_with.php) (slide 36)
    - [`fdiv()`](code/4_functions/3_fdiv.php) (slide 37)
    - [`get_debug_type()`](code/4_functions/4_get_debug_type.php) (slide 38)
    - [`get_resource_id()`](code/4_functions/5_get_resource_id.php) (slide 39)
- Breaking changes (slides 40-42)
    - Breaking changes (slide 41)
    - Reclassified engine warnings (slide 42)
