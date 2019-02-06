<template>
<!-- 	<div>
		<div class="message-box">
                <div class="top">
                    <span class="user-name is-pulled-left">Susie Lampan</span>
                    <div class="control is-pulled-right">
                        <div class="select select-user-box">
                            <select class="select-user">
                            <option>Facebook</option>
                            <option>With options</option>
                            </select>
                        </div>
                    </div>
                </div>
                <div class="messages">
                    <div class="message-line received">
                        <p>Hour of Operation?</p>
                    </div>
                    <div class="message-line sent">
                        <p>Let me check</p>
                    </div>
                    <div class="message-line sent">
                        <p>Is this for a special occasion?</p>
                    </div>
                    <div class="message-line received">
                        <p>Are there any children in the party?</p>
                    </div>
                    <div class="message-line sent">
                        <p>Valet Parking? Let me check</p>
                    </div>
                </div>
                <div class="suggestions">
                    <a href="#">Free for party?</a>
                    <a href="#">Concert Anywhere?</a>
                </div>
                <div class="message-checkbox">
                    <div class="field">
                        <input class="is-checkradio is-info" id="checkbox-template" type="checkbox" name="checkbox-template" checked="checked">
                        <label for="checkbox-template">Choose Template</label>
                    </div>
                    <div class="field">
                        <input class="is-checkradio is-info" id="checkbox-survay" type="checkbox" name="checkbox-survay">
                        <label for="checkbox-survay">Send Survay</label>
                    </div>
                </div>
                <div class="message-field">
                    <input type="text" placeholder="Type your message here…" />
                </div>
            </div>
	</div> -->
</template>
<script>
export default {
    mounted: function () {
        axios.post('/botman').then(res => {
            console.log(res);
        }).catch(err => {
            console.log(err);
        })
    }
}	
</script>
<style>
	
</style>