## Future

- [Future of the decorators](https://github.com/nestjs/nest/issues/10959#issuecomment-1406131938)

## Won't be introduced

- [More HTTP exception classes to `@nestjs/common` - including new entries to `HttpStatus` enum](https://github.com/nestjs/nest/issues/6657#issuecomment-799214959)

- [Multi option for providers (Angular's feature)](https://github.com/nestjs/nest/issues/770#issuecomment-1412029060)

  - <details><summary>Community-made workarounds</summary>

    1. https://dev.to/micalevisk/nestjs-tip-multi-value-providers-almost-like-multi-from-angular-1c63
    2. https://github.com/Sikora00/multi

    </details>

- [`inject()` function to inject dependencies (Angular's feature)](https://github.com/nestjs/nest/issues/10586#issuecomment-1324707932)

- [Custom condition in `@Catch()`](https://github.com/nestjs/nest/issues/4516)
  - <details><summary>Community-made workarounds</summary>

    1. https://dev.to/micalevisk/nestjs-tip-fine-grained-exception-filtering-for-the-same-exception-class-5ha5

    </details>

## Informative

- [You can't bundle the entire app as you can do with a FE app](https://github.com/nestjs/nest/issues/1706#issuecomment-579248915)
- [You can't use `Test.createTestingModule()` if your app is injecting the `HttpAdapterHost` somewhere](https://github.com/nestjs/nest/issues/8076#issuecomment-926542597). Use `NestFactory.create` instead.
