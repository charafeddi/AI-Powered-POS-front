<template>
    <div class="page-content">
        <div class="page-info">
            <nav aria-label="breadcrumb">
                <ol class="breadcrumb">
                    <li class="breadcrumb-item"><a href="#">Apps</a></li>
                    <li class="breadcrumb-item active" aria-current="page">Mailbox</li>
                </ol>
            </nav>
            <div class="page-options">
                <a href="#" @click.prevent="compose" class="btn btn-primary" id="mail-compose">Compose</a>
            </div>
        </div>
        <div class="main-wrapper">
            <div class="row">
                <div class="col-lg-3">
                    <div class="card">
                        <div class="card-body">
                            <ul class="mailbox-menu list-unstyled">
                                <li><a href="#" class="active">Inbox<span class="badge badge-pill badge-success float-right">21</span></a></li>
                                <li><a href="#">Sent</a></li>
                                <li><a href="#">Important<span class="badge badge-pill badge-warning float-right">6</span></a></li>
                                <li><a href="#">Promotions<span class="badge badge-pill badge-danger float-right">11</span></a></li>
                                <li><a href="#">Social<span class="badge badge-pill badge-info float-right">3</span></a></li>
                                <li><a href="#">Drafts</a></li>
                                <li><a href="#">Spam</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="col-lg-9">
                    <div class="card">
                        <div class="card-body">
                            <div class="inbox-options">
                                <div class="inbox-checkbox-all">
                                    <div class="custom-control custom-checkbox form-group">
                                        <input type="checkbox" class="custom-control-input" id="check-all-mail">
                                        <label class="custom-control-label" for="check-all-mail"></label>
                                    </div>
                                </div>
                                <div class="inbox-page-count">
                                    Showing 1-50 of 3089
                                </div>
                                <div class="inbox-search">
                                        <input type="text" class="form-control" id="searchInbox" placeholder="Search inbox">
                                </div>
                            </div>
                            <ul class="inbox-list list-unstyled">
                                <li>
                                    <a href="javascript: void(0);">
                                        <div class="mail-checkbox">
                                            <div class="custom-control custom-checkbox form-group">
                                                <input type="checkbox" class="custom-control-input" id="mail1">
                                                <label class="custom-control-label" for="mail1"></label>
                                            </div>
                                        </div>
                                        <div class="mail-author">
                                            <img src="@/assets/img/avatars/profile-image.png"> <span>William Adams</span>
                                        </div>
                                        <div class="mail-title">
                                            Nullam quis risus eget urna mollis ornare vel eu leo
                                        </div>
                                        <div class="mail-date">
                                            2hrs
                                        </div>
                                        <div class="mail-star">
                                            <i class="material-icons">star_border</i>
                                        </div>
                                    </a>
                                </li>
                                <li>
                                    <a href="javascript: void(0);">
                                        <div class="mail-checkbox">
                                            <div class="custom-control custom-checkbox form-group">
                                                <input type="checkbox" class="custom-control-input" id="mail2">
                                                <label class="custom-control-label" for="mail2"></label>
                                            </div>
                                        </div>
                                        <div class="mail-author">
                                            <img src="@/assets/img/avatars/profile-image-2.png"> <span>Allen Ford</span>
                                        </div>
                                        <div class="mail-title">
                                            Lorem ipsum dolor sit amet, consectetuer adipiscing elit
                                        </div>
                                        <div class="mail-date">
                                            14 Apr
                                        </div>
                                        <div class="mail-star">
                                            <i class="material-icons">star_border</i>
                                        </div>
                                    </a>
                                </li>
                                <li>
                                    <a href="javascript: void(0);">
                                        <div class="mail-checkbox">
                                            <div class="custom-control custom-checkbox form-group">
                                                <input type="checkbox" class="custom-control-input" id="mail3">
                                                <label class="custom-control-label" for="mail3"></label>
                                            </div>
                                        </div>
                                        <div class="mail-author">
                                            <img src="@/assets/img/avatars/profile-image-3.jpg"> <span>Louis Morgan</span>
                                        </div>
                                        <div class="mail-title">
                                            Nam quis nulla aliquet elit ornare iaculis
                                        </div>
                                        <div class="mail-date">
                                            12 Apr
                                        </div>
                                        <div class="mail-star">
                                            <i class="material-icons">star_border</i>
                                        </div>
                                    </a>
                                </li>
                                <li>
                                    <a href="javascript: void(0);">
                                        <div class="mail-checkbox">
                                            <div class="custom-control custom-checkbox form-group">
                                                <input type="checkbox" class="custom-control-input" id="mail4">
                                                <label class="custom-control-label" for="mail4"></label>
                                            </div>
                                        </div>
                                        <div class="mail-author">
                                            <img src="@/assets/img/avatars/profile-image-1.png"> <span>David Simpson</span>
                                        </div>
                                        <div class="mail-title">
                                            Ut sed risus eget nunc mattis dignissim a sit amet lectus
                                        </div>
                                        <div class="mail-date">
                                            12 Apr
                                        </div>
                                        <div class="mail-star">
                                            <i class="material-icons">star_border</i>
                                        </div>
                                    </a>
                                </li>
                                <li>
                                    <a href="javascript: void(0);">
                                        <div class="mail-checkbox">
                                            <div class="custom-control custom-checkbox form-group">
                                                <input type="checkbox" class="custom-control-input" id="mail5">
                                                <label class="custom-control-label" for="mail5"></label>
                                            </div>
                                        </div>
                                        <div class="mail-author">
                                            <img src="@/assets/img/avatars/profile-image.png"> <span>Emilia Clark</span>
                                        </div>
                                        <div class="mail-title">
                                            Orci varius natoque penatibus et magnis dis parturient montes
                                        </div>
                                        <div class="mail-date">
                                            11 Apr
                                        </div>
                                        <div class="mail-star">
                                            <i class="material-icons">star_border</i>
                                        </div>
                                    </a>
                                </li>
                                <li>
                                    <a href="javascript: void(0);">
                                        <div class="mail-checkbox">
                                            <div class="custom-control custom-checkbox form-group">
                                                <input type="checkbox" class="custom-control-input" id="mail6">
                                                <label class="custom-control-label" for="mail6"></label>
                                            </div>
                                        </div>
                                        <div class="mail-author">
                                            <img src="@/assets/img/avatars/profile-image.png"> <span>William Adams</span>
                                        </div>
                                        <div class="mail-title">
                                            Nullam quis risus eget urna mollis ornare vel eu leo
                                        </div>
                                        <div class="mail-date">
                                            10 Apr
                                        </div>
                                        <div class="mail-star">
                                            <i class="material-icons">star_border</i>
                                        </div>
                                    </a>
                                </li>
                                <li>
                                    <a href="javascript: void(0);">
                                        <div class="mail-checkbox">
                                            <div class="custom-control custom-checkbox form-group">
                                                <input type="checkbox" class="custom-control-input" id="mail7">
                                                <label class="custom-control-label" for="mail7"></label>
                                            </div>
                                        </div>
                                        <div class="mail-author">
                                            <img src="@/assets/img/avatars/profile-image-2.png"> <span>Allen Ford</span>
                                        </div>
                                        <div class="mail-title">
                                            Lorem ipsum dolor sit amet, consectetuer adipiscing elit
                                        </div>
                                        <div class="mail-date">
                                            9 Apr
                                        </div>
                                        <div class="mail-star">
                                            <i class="material-icons">star_border</i>
                                        </div>
                                    </a>
                                </li>
                                <li>
                                    <a href="javascript: void(0);">
                                        <div class="mail-checkbox">
                                            <div class="custom-control custom-checkbox form-group">
                                                <input type="checkbox" class="custom-control-input" id="mail8">
                                                <label class="custom-control-label" for="mail8"></label>
                                            </div>
                                        </div>
                                        <div class="mail-author">
                                            <img src="@/assets/img/avatars/profile-image-3.jpg"> <span>Louis Morgan</span>
                                        </div>
                                        <div class="mail-title">
                                            Nam quis nulla aliquet elit ornare iaculis
                                        </div>
                                        <div class="mail-date">
                                            9 Apr
                                        </div>
                                        <div class="mail-star">
                                            <i class="material-icons">star_border</i>
                                        </div>
                                    </a>
                                </li>
                                <li>
                                    <a href="javascript: void(0);">
                                        <div class="mail-checkbox">
                                            <div class="custom-control custom-checkbox form-group">
                                                <input type="checkbox" class="custom-control-input" id="mail9">
                                                <label class="custom-control-label" for="mail9"></label>
                                            </div>
                                        </div>
                                        <div class="mail-author">
                                            <img src="@/assets/img/avatars/profile-image-1.png"> <span>David Simpson</span>
                                        </div>
                                        <div class="mail-title">
                                            Ut sed risus eget nunc mattis dignissim a sit amet lectus
                                        </div>
                                        <div class="mail-date">
                                            8 Apr
                                        </div>
                                        <div class="mail-star">
                                            <i class="material-icons">star_border</i>
                                        </div>
                                    </a>
                                </li>
                                <li>
                                    <a href="javascript: void(0);">
                                        <div class="mail-checkbox">
                                            <div class="custom-control custom-checkbox form-group">
                                                <input type="checkbox" class="custom-control-input" id="mail10">
                                                <label class="custom-control-label" for="mail10"></label>
                                            </div>
                                        </div>
                                        <div class="mail-author">
                                            <img src="@/assets/img/avatars/profile-image.png"> <span>Emilia Clark</span>
                                        </div>
                                        <div class="mail-title">
                                            Orci varius natoque penatibus et magnis dis parturient montes
                                        </div>
                                        <div class="mail-date">
                                            7 Apr
                                        </div>
                                        <div class="mail-star">
                                            <i class="material-icons">star_border</i>
                                        </div>
                                    </a>
                                </li>
                                <li>
                                    <a href="javascript: void(0);">
                                        <div class="mail-checkbox">
                                            <div class="custom-control custom-checkbox form-group">
                                                <input type="checkbox" class="custom-control-input" id="mail11">
                                                <label class="custom-control-label" for="mail11"></label>
                                            </div>
                                        </div>
                                        <div class="mail-author">
                                            <img src="@/assets/img/avatars/profile-image.png"> <span>William Adams</span>
                                        </div>
                                        <div class="mail-title">
                                            Nullam quis risus eget urna mollis ornare vel eu leo
                                        </div>
                                        <div class="mail-date">
                                            4 Apr
                                        </div>
                                        <div class="mail-star">
                                            <i class="material-icons">star_border</i>
                                        </div>
                                    </a>
                                </li>
                            </ul>
                            <div class="inbox-pagination">
                                <nav>
                                    <ul class="pagination">
                                        <li class="page-item disabled"><a class="page-link" href="#">Previous</a></li>
                                        <li class="page-item active"><a class="page-link" href="#">1</a></li>
                                        <li class="page-item"><a class="page-link" href="#">2</a></li>
                                        <li class="page-item"><a class="page-link" href="#">3</a></li>
                                        <li class="page-item"><a class="page-link" href="#">Next</a></li>
                                    </ul>
                                </nav>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
import { useStore } from 'vuex';
import { ref, onMounted } from 'vue';
export default {
    name:'MailSystem',
    setup() {
        const store = useStore();

        const compose = () => {
            store.dispatch('mail/ComposeMail', true);
        };

        return {
            compose,
        };
    }
}
</script>