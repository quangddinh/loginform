<template>
    <div class="container">
        <Navbar />
        <ChatWindow />
        <NewChatForm />
    </div>
</template>

<script>
import Navbar from "../components/Navbar.vue";
import NewChatForm from "../components/NewChatForm.vue";
import ChatWindow from "../components/ChatWindow.vue";
import getUser from "../composables/getUser";
import { useRouter } from "vue-router";

export default {
    components: { Navbar, NewChatForm, ChatWindow },
};
</script>

<style></style>
