<template>
    <div>
        <div class="bg-overlay"></div>
        <div class="wrapper-page">
            <div class="container-fluid p-0">
                <div class="card">
                    <div class="card-body">

                        <div class="text-center mt-4">
                            <div class="mb-3">
                                <router-link to="/">
                                <!-- <a href="index.html" class="auth-logo"> -->
                                    <img src="../../../public/images/logo.png" height="50" class="logo-dark mx-auto" alt="">
                                    <!-- <img src="{{ asset('images/logo-white.png') }}" height="50" class="logo-light mx-auto" alt=""> -->
                                <!-- </a> -->
                                </router-link>
                            </div>
                        </div>
                        <router-view></router-view>
                        <!-- end -->
                    </div>
                    <!-- end cardbody -->
                </div>
                <!-- end card -->
            </div>
            <!-- end container -->
        </div>
    </div>        
</template>