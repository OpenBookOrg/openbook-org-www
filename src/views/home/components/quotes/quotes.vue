<template>
    <div class="columns">
        <div class="column">
            <div class="box quote-box">
                <article class="media">
                    <div class="media-left">
                        <figure class="image is-64x64">
                            <img class="is-rounded"
                                 :src="joelPhoto"
                                 alt="Image">
                        </figure>
                    </div>
                    <div class="media-content">
                        <div class="content">
                            <p>
                                <strong>{{ $t('home:quotes.joel_name') }}</strong>
                                <br>
                                <small class="quote-box-occupation">{{ $t('home:quotes.joel_title') }}</small>
                                <br>
                                <span class="quote-box-content">
                                    {{ $t('home:quotes.joel_quote') }}
                                </span>
                            </p>
                        </div>
                    </div>
                </article>
            </div>
        </div>
        <div class="column">
            <div class="box quote-box">
                <article class="media">
                    <div class="media-left">
                        <figure class="image is-64x64">
                            <img class="is-rounded"
                                 :src="vincentPhoto"
                                 alt="Image">
                        </figure>
                    </div>
                    <div class="media-content">
                        <div class="content">
                            <p>
                                <strong>{{ $t('home:quotes.vincent_name') }}</strong>
                                <br>
                                <small class="quote-box-occupation">{{ $t('home:quotes.vincent_title') }}</small>
                                <br>
                                <span class="quote-box-content">
                                    {{ $t('home:quotes.vincent_quote') }}
                                </span>
                            </p>
                        </div>
                    </div>
                </article>
            </div>
        </div>
        <div class="column">
            <div class="box quote-box">
                <article class="media">
                    <div class="media-left">
                        <figure class="image is-64x64">
                            <img class="is-rounded"
                                 :src="philPhoto"
                                 alt="Image">
                        </figure>
                    </div>
                    <div class="media-content">
                        <div class="content">
                            <p>
                                <strong>{{ $t('home:quotes.phil_name') }}</strong>
                                <br>
                                <small class="quote-box-occupation">
                                    {{ $t('home:quotes.phil_title') }}
                                </small>
                                <br>
                                <span class="quote-box-content">
                                     {{ $t('home:quotes.phil_quote') }}
                                </span>
                            </p>
                        </div>
                    </div>
                </article>
            </div>
        </div>
    </div>
</template>

<style lang="scss">
    .quote-box {
        height: 100%;
    }

    .quote-box-occupation {
        font-weight: lighter;
    }

    .quote-box-content {
        display: inline-block;
        padding-top: 0.5rem;
    }
</style>

<script>
    import philPhoto from './assets/phil-min.jpg';
    import vincentPhoto from './assets/vincent-min.jpg';
    import joelPhoto from './assets/joel-min.jpg';

    export default {
        name: 'ob-quotes',
        data() {
            return {
                philPhoto: philPhoto,
                vincentPhoto: vincentPhoto,
                joelPhoto: joelPhoto
            }
        }
    }
</script>
