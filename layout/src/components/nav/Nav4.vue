<template>
    <v-card 
    class="mx-auto"
    max-width="430">
    <v-layout>
        <v-app-bar color="info" density="prominent">
        <template v-slot:prepend>
            <v-app-bar-nav-icon></v-app-bar-nav-icon>
        </template>
        <v-app-bar-title>My Recent Trips</v-app-bar-title>
<template v-slot:append>
    <v-btn icon>
        <v-icon>mdi-dots-vertical</v-icon>
    </v-btn>
</template>            
        </v-app-bar>
        <v-main>
            <v-container fluid>
                <v-card
                class="mb-2"
                density="compact"
                prepend-avatar="https://randomuser.me/api/portraits/women/10.jpg"
                subtitle="Olivia"
                variant="text"
                border>
            <v-img height="128" src="http://picsum.photos/512/128?image=660" cover></v-img>
            <v-card-text>Happy New Year!!</v-card-text>
            <template v-slot:actions>
                <v-btn color="primary" variant="flat">View more</v-btn>
                <v-btn color="primary" variant="text">See an Map</v-btn>
                <v-btn color="primary" variant="tonal">back</v-btn>
                <v-btn color="primary" variant="outlined">next</v-btn>
            </template>
            </v-card>

            </v-container>
        </v-main>
    </v-layout>
    </v-card>
</template>