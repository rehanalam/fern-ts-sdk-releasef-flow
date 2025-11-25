# Reference
## pet
<details><summary><code>client.pet.<a href="/src/api/resources/pet/client/Client.ts">addPet</a>({ ...params }) -> FernPerstoreReleaseFlowApi.Pet</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Add a new pet to the store.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.pet.addPet({
    name: "doggie",
    photoUrls: ["photoUrls"]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FernPerstoreReleaseFlowApi.Pet` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PetClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.pet.<a href="/src/api/resources/pet/client/Client.ts">updatePet</a>({ ...params }) -> FernPerstoreReleaseFlowApi.Pet</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update an existing pet by Id.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.pet.updatePet({
    name: "doggie",
    photoUrls: ["photoUrls"]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FernPerstoreReleaseFlowApi.Pet` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PetClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.pet.<a href="/src/api/resources/pet/client/Client.ts">findPetsByStatus</a>({ ...params }) -> FernPerstoreReleaseFlowApi.Pet[]</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Multiple status values can be provided with comma separated strings.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.pet.findPetsByStatus({
    status: "available"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FernPerstoreReleaseFlowApi.FindPetsByStatusRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PetClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.pet.<a href="/src/api/resources/pet/client/Client.ts">findPetsByTags</a>({ ...params }) -> FernPerstoreReleaseFlowApi.Pet[]</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Multiple tags can be provided with comma separated strings. Use tag1, tag2, tag3 for testing.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.pet.findPetsByTags();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FernPerstoreReleaseFlowApi.FindPetsByTagsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PetClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.pet.<a href="/src/api/resources/pet/client/Client.ts">getPetById</a>({ ...params }) -> FernPerstoreReleaseFlowApi.Pet</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns a single pet.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.pet.getPetById({
    petId: 1000000
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FernPerstoreReleaseFlowApi.GetPetByIdRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PetClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.pet.<a href="/src/api/resources/pet/client/Client.ts">updatePetWithForm</a>({ ...params }) -> FernPerstoreReleaseFlowApi.Pet</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Updates a pet resource based on the form data.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.pet.updatePetWithForm({
    petId: 1000000
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FernPerstoreReleaseFlowApi.UpdatePetWithFormRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PetClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.pet.<a href="/src/api/resources/pet/client/Client.ts">deletePet</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Delete a pet.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.pet.deletePet({
    petId: 1000000
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FernPerstoreReleaseFlowApi.DeletePetRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PetClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## store
<details><summary><code>client.store.<a href="/src/api/resources/store/client/Client.ts">getInventory</a>() -> Record<string, number></code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns a map of status codes to quantities.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.store.getInventory();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `StoreClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.store.<a href="/src/api/resources/store/client/Client.ts">placeOrder</a>({ ...params }) -> FernPerstoreReleaseFlowApi.Order</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Place a new order in the store.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.store.placeOrder({});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FernPerstoreReleaseFlowApi.Order` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `StoreClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.store.<a href="/src/api/resources/store/client/Client.ts">getOrderById</a>({ ...params }) -> FernPerstoreReleaseFlowApi.Order</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

For valid response try integer IDs with value <= 5 or > 10. Other values will generate exceptions.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.store.getOrderById({
    orderId: 1000000
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FernPerstoreReleaseFlowApi.GetOrderByIdRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `StoreClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.store.<a href="/src/api/resources/store/client/Client.ts">deleteOrder</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

For valid response try integer IDs with value < 1000. Anything above 1000 or non-integers will generate API errors.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.store.deleteOrder({
    orderId: 1000000
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FernPerstoreReleaseFlowApi.DeleteOrderRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `StoreClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## user
<details><summary><code>client.user.<a href="/src/api/resources/user/client/Client.ts">createUser</a>({ ...params }) -> FernPerstoreReleaseFlowApi.User</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

This can only be done by the logged in user.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.user.createUser({});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FernPerstoreReleaseFlowApi.User` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `UserClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.user.<a href="/src/api/resources/user/client/Client.ts">createUsersWithListInput</a>({ ...params }) -> FernPerstoreReleaseFlowApi.User</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Creates list of users with given input array.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.user.createUsersWithListInput([{}]);

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FernPerstoreReleaseFlowApi.User[]` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `UserClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.user.<a href="/src/api/resources/user/client/Client.ts">loginUser</a>({ ...params }) -> string</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Log into the system.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.user.loginUser();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FernPerstoreReleaseFlowApi.LoginUserRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `UserClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.user.<a href="/src/api/resources/user/client/Client.ts">logoutUser</a>() -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Log user out of the system.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.user.logoutUser();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `UserClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.user.<a href="/src/api/resources/user/client/Client.ts">getUserByName</a>({ ...params }) -> FernPerstoreReleaseFlowApi.User</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get user detail based on username.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.user.getUserByName({
    username: "username"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FernPerstoreReleaseFlowApi.GetUserByNameRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `UserClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.user.<a href="/src/api/resources/user/client/Client.ts">updateUser</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

This can only be done by the logged in user.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.user.updateUser({
    username: "username",
    body: {}
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FernPerstoreReleaseFlowApi.UpdateUserRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `UserClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.user.<a href="/src/api/resources/user/client/Client.ts">deleteUser</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

This can only be done by the logged in user.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.user.deleteUser({
    username: "username"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FernPerstoreReleaseFlowApi.DeleteUserRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `UserClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>
