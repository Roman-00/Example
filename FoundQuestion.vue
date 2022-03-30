<template>
    <div
        class="found-question-form"
    >
        <h2 class="found-question-form__title">
            Нашли то, что искали?
        </h2>

        <div class="found-question-form__buttons">
            <button class="found-question-form__buttons-success">
                Да
            </button>

            <button class="found-question-form__buttons-negative">
                Нет
            </button>
        </div>
    </div>
</template>

<style lang="scss">
@import '../style/variables.scss';

.found-question-form {
    padding: 20px 0;

    &__title {
        margin-bottom: 20px;
        font-size: 1rem;
        font-weight: $font-semi;
        line-height: 24px;
        color: $black-primary;
    }

    &__buttons {
        display: flex;
        align-items: center;
        justify-content: space-between;
    }

    button {
        width: 100%;
        max-width: 156px;
        padding: 10px 0;
        font-size: 1rem;
        font-weight: $font-normal;
        line-height: 24px;
        border: 1px solid rgba($black-primary, 0.1);
        border-radius: $radius-medium;
        background: $white;
        filter: drop-shadow(0 2px 4px rgba($black-primary, 0.1));
        color: $blue-primary;
    }
}
</style>
