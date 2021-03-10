<template>
    <div>
        <v-container>
            <v-row>
                <v-col lg="8">
                    <section>
                        <div class="d-flex">
                            <h1>Featured Stories</h1>
                            <v-select :items="items" label="Populer Stories" outlined class="dropdown"></v-select>
                        </div>
                        <v-row class="stories-image">
                            <v-col lg="3">
                                <v-card max-height="300" max-width="200" style="box-shadow: none;">
                                    <img src="https://images.unsplash.com/photo-1614783824364-a5cfca73957c?ixid=MXwxMjA3fDB8MHx0b3BpYy1mZWVkfDI4fDZzTVZqVExTa2VRfHxlbnwwfHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="">
                                </v-card>
                            </v-col>
                            <v-col lg="3">
                                <v-card max-height="300" max-width="200" style="box-shadow: none;">
                                    <img src="https://images.unsplash.com/photo-1614755193276-88ca7b035003?ixid=MXwxMjA3fDB8MHx0b3BpYy1mZWVkfDI5fDZzTVZqVExTa2VRfHxlbnwwfHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="">
                                </v-card>
                            </v-col>
                            <v-col lg="3">
                                <v-card max-height="300" max-width="200" style="box-shadow: none;">
                                    <img src="https://images.unsplash.com/photo-1614977195497-37b743bdffee?ixid=MXwxMjA3fDB8MHx0b3BpYy1mZWVkfDI2fDZzTVZqVExTa2VRfHxlbnwwfHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="">
                                </v-card>
                            </v-col>
                            <v-col lg="3">
                                <v-card max-height="300" max-width="200" style="box-shadow: none;">
                                    <img src="https://images.unsplash.com/photo-1615143303521-ea62b01267e3?ixid=MXwxMjA3fDB8MHx0b3BpYy1mZWVkfDIzfDZzTVZqVExTa2VRfHxlbnwwfHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="">
                                </v-card>
                            </v-col>
                        </v-row>
                    </section>
                    <section class="mt-5">
                        <div class="d-flex">
                            <h1>Latest Feed</h1>
                            <div class="d-flex ml-auto">
                                <v-icon medium class="pr-3">menu</v-icon>
                                <v-icon medium style="color: #ff003c;">grid_view</v-icon>
                            </div>
                        </div>
                        <v-row class="image-potrait">
                            <v-col lg="4">
                                <v-card max-height="300" max-width="600" style="box-shadow: none;">
                                    <img src="https://images.unsplash.com/photo-1615148536759-8fae933d8ff1?ixid=MXwxMjA3fDB8MHx0b3BpYy1mZWVkfDIyfDZzTVZqVExTa2VRfHxlbnwwfHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="">
                                </v-card>
                            </v-col>
                            <v-col lg="4">
                                <v-card max-height="300" max-width="600" style="box-shadow: none;">
                                    <img src="https://images.unsplash.com/photo-1613918794803-5411f8fc8147?ixid=MXwxMjA3fDB8MHx0b3BpYy1mZWVkfDIxfDZzTVZqVExTa2VRfHxlbnwwfHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="">
                                </v-card>
                            </v-col>
                            <v-col lg="4">
                                <v-card max-height="300" max-width="600" style="box-shadow: none;">
                                    <img src="https://images.unsplash.com/photo-1614850462576-2eb85335b63b?ixid=MXwxMjA3fDB8MHx0b3BpYy1mZWVkfDE3fDZzTVZqVExTa2VRfHxlbnwwfHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="">
                                </v-card>
                            </v-col>
                        </v-row>
                        <v-row class="image-landscape">
                            <v-col lg="4">
                                <v-card max-height="100" max-width="600" style="box-shadow: none;">
                                    <img src="https://images.unsplash.com/photo-1551509134-eb7c5ea9ad2d?ixid=MXwxMjA3fDB8MHx0b3BpYy1mZWVkfDExfDZzTVZqVExTa2VRfHxlbnwwfHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="">
                                </v-card>
                            </v-col>
                            <v-col lg="4">
                                <v-card max-height="100" max-width="600" style="box-shadow: none;">
                                    <img src="https://images.unsplash.com/photo-1615271292858-7107dcb37363?ixid=MXwxMjA3fDB8MHx0b3BpYy1mZWVkfDE0fDZzTVZqVExTa2VRfHxlbnwwfHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="">
                                </v-card>
                            </v-col>
                            <v-col lg="4">
                                <v-card max-height="100" max-width="600" style="box-shadow: none;">
                                    <img src="https://images.unsplash.com/photo-1615232934320-87b37b0ff5ab?ixid=MXwxMjA3fDB8MHx0b3BpYy1mZWVkfDE5fDZzTVZqVExTa2VRfHxlbnwwfHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="">
                                </v-card>
                            </v-col>
                            <v-col lg="4">
                                <v-card max-height="100" max-width="600" style="box-shadow: none;">
                                    <img src="https://images.unsplash.com/photo-1614862053138-10ca7a58866e?ixid=MXwxMjA3fDB8MHx0b3BpYy1mZWVkfDQyfDZzTVZqVExTa2VRfHxlbnwwfHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="">
                                </v-card>
                            </v-col>
                            <v-col lg="4">
                                <v-card max-height="100" max-width="600" style="box-shadow: none;">
                                    <img src="https://images.unsplash.com/photo-1614889817091-34e8c54b8c2f?ixid=MXwxMjA3fDB8MHx0b3BpYy1mZWVkfDM5fDZzTVZqVExTa2VRfHxlbnwwfHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="">
                                </v-card>
                            </v-col>
                            <v-col lg="4">
                                <v-card max-height="100" max-width="600" style="box-shadow: none;">
                                    <img src="https://images.unsplash.com/photo-1569078201377-7a28757ecb13?ixid=MXwxMjA3fDB8MHx0b3BpYy1mZWVkfDI3fDZzTVZqVExTa2VRfHxlbnwwfHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="">
                                </v-card>
                            </v-col>
                        </v-row>
                    </section>
                </v-col>
                <v-col lg="4">
                    <div class="profile-image">
                        <img src="../assets/image.jpg" alt="">
                    </div>
                    <h2>BENJAMIN HARDMAN</h2>
                    <div class="d-flex">
                        <p>882 <span>Photos</span></p>
                        <p class="pl-5">527k <span>Followers</span></p>
                    </div>
                    <p class="desc">Benjamin is a freelance photographer based in Iceland, represented across the nordic regions by Norour agency.</p>
                    <p class="desc">Five years ago, Benjamin embarked on his first photographic mission in an Arctic winter climate... <span class="more">Read More</span></p>
                    <p>Location</p>
                    <span>Based in Iceland.</span>
                    <p class="pt-5">Profession</p>
                    <span>Photographer</span>
                </v-col>
            </v-row>
        </v-container>
    </div>
</template>

<script>
    export default {
        name: "Main",
        data: () => ({
            items: ['Foo', 'Bar', 'Fizz', 'Buzz']
        })
    }
</script>

<style scoped>
h1 {
    padding: 30px 0px 20px 0px;
}

h2 {
    padding-top: 20px;
}

p {
    font-weight: bold;
}

p.desc {
    color: rgba(0,0,0,.5);
    font-weight: normal;
}

span {
    color: rgba(0,0,0,.5);
    font-weight: normal;
}

span.more {
    font-weight: bold;
    color: rgba(0,0,0,.85);
}

.dropdown {
    padding: 20px 0px 0px 170px !important;
}

.profile-image img {
    max-width: 100%;
    height: auto;
    object-fit: cover;
    margin-top: 20px;
    border-radius: 10px;
}

.stories-image img {
    width: 150px;
    height: 200px;
    object-fit: cover;
}

.image-potrait img {
    width: 200px;
    height: 300px;
}

.image-landscape img {
    width: 200px;
    height: 100px;
    object-fit: cover;
}
</style>