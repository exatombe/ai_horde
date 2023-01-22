[@zeldafan0225/stable_horde](../readme.md) / [Exports](../modules.md) / UserDetailsStable

# Interface: UserDetailsStable

## Hierarchy

- [`UserDetails`](UserDetails.md)

  ↳ **`UserDetailsStable`**

## Table of contents

### Properties

- [concurrency](UserDetailsStable.md#concurrency)
- [contact](UserDetailsStable.md#contact)
- [contributions](UserDetailsStable.md#contributions)
- [evaluating\_kudos](UserDetailsStable.md#evaluating_kudos)
- [id](UserDetailsStable.md#id)
- [kudos](UserDetailsStable.md#kudos)
- [kudos\_details](UserDetailsStable.md#kudos_details)
- [moderator](UserDetailsStable.md#moderator)
- [monthly\_kudos](UserDetailsStable.md#monthly_kudos)
- [pseudonymous](UserDetailsStable.md#pseudonymous)
- [suspicious](UserDetailsStable.md#suspicious)
- [trusted](UserDetailsStable.md#trusted)
- [usage](UserDetailsStable.md#usage)
- [username](UserDetailsStable.md#username)
- [worker\_count](UserDetailsStable.md#worker_count)
- [worker\_ids](UserDetailsStable.md#worker_ids)
- [worker\_invited](UserDetailsStable.md#worker_invited)

## Properties

### concurrency

• `Optional` **concurrency**: `number`

How many concurrent generations this user may request.

#### Inherited from

[UserDetails](UserDetails.md).[concurrency](UserDetails.md#concurrency)

#### Defined in

[index.ts:1875](https://github.com/ZeldaFan0225/stable_horde/blob/b03d78a/index.ts#L1875)

___

### contact

• `Optional` **contact**: `string`

(Privileged) Contact details for the horde admins to reach the user in case of emergency.

**`Example`**

```ts
email@example.com
```

#### Inherited from

[UserDetails](UserDetails.md).[contact](UserDetails.md#contact)

#### Defined in

[index.ts:1895](https://github.com/ZeldaFan0225/stable_horde/blob/b03d78a/index.ts#L1895)

___

### contributions

• `Optional` **contributions**: [`ContributionsDetailsStable`](ContributionsDetailsStable.md)

#### Defined in

[index.ts:1862](https://github.com/ZeldaFan0225/stable_horde/blob/b03d78a/index.ts#L1862)

___

### evaluating\_kudos

• `Optional` **evaluating\_kudos**: `number`

(Privileged) The amount of Evaluating Kudos this untrusted user has from generations and uptime. When this number reaches 50000, they automatically become trusted.

#### Inherited from

[UserDetails](UserDetails.md).[evaluating_kudos](UserDetails.md#evaluating_kudos)

#### Defined in

[index.ts:1873](https://github.com/ZeldaFan0225/stable_horde/blob/b03d78a/index.ts#L1873)

___

### id

• `Optional` **id**: `number`

The user unique ID. It is always an integer.

#### Inherited from

[UserDetails](UserDetails.md).[id](UserDetails.md#id)

#### Defined in

[index.ts:1869](https://github.com/ZeldaFan0225/stable_horde/blob/b03d78a/index.ts#L1869)

___

### kudos

• `Optional` **kudos**: `number`

The amount of Kudos this user has. The amount of Kudos determines the priority when requesting image generations.

#### Inherited from

[UserDetails](UserDetails.md).[kudos](UserDetails.md#kudos)

#### Defined in

[index.ts:1871](https://github.com/ZeldaFan0225/stable_horde/blob/b03d78a/index.ts#L1871)

___

### kudos\_details

• `Optional` **kudos\_details**: [`UserKudosDetails`](UserKudosDetails.md)

#### Inherited from

[UserDetails](UserDetails.md).[kudos_details](UserDetails.md#kudos_details)

#### Defined in

[index.ts:1880](https://github.com/ZeldaFan0225/stable_horde/blob/b03d78a/index.ts#L1880)

___

### moderator

• `Optional` **moderator**: `boolean`

This user is a Horde moderator.

#### Inherited from

[UserDetails](UserDetails.md).[moderator](UserDetails.md#moderator)

#### Defined in

[index.ts:1879](https://github.com/ZeldaFan0225/stable_horde/blob/b03d78a/index.ts#L1879)

___

### monthly\_kudos

• `Optional` **monthly\_kudos**: [`MonthlyKudos`](MonthlyKudos.md)

#### Inherited from

[UserDetails](UserDetails.md).[monthly_kudos](UserDetails.md#monthly_kudos)

#### Defined in

[index.ts:1884](https://github.com/ZeldaFan0225/stable_horde/blob/b03d78a/index.ts#L1884)

___

### pseudonymous

• `Optional` **pseudonymous**: `boolean`

If true, this user has not registered using an oauth service.

#### Inherited from

[UserDetails](UserDetails.md).[pseudonymous](UserDetails.md#pseudonymous)

#### Defined in

[index.ts:1890](https://github.com/ZeldaFan0225/stable_horde/blob/b03d78a/index.ts#L1890)

___

### suspicious

• `Optional` **suspicious**: `number`

(Privileged) How much suspicion this user has accumulated

#### Inherited from

[UserDetails](UserDetails.md).[suspicious](UserDetails.md#suspicious)

#### Defined in

[index.ts:1888](https://github.com/ZeldaFan0225/stable_horde/blob/b03d78a/index.ts#L1888)

___

### trusted

• `Optional` **trusted**: `boolean`

This user is a trusted member of the Horde.

#### Inherited from

[UserDetails](UserDetails.md).[trusted](UserDetails.md#trusted)

#### Defined in

[index.ts:1886](https://github.com/ZeldaFan0225/stable_horde/blob/b03d78a/index.ts#L1886)

___

### usage

• `Optional` **usage**: [`UsageDetailsStable`](UsageDetailsStable.md)

#### Defined in

[index.ts:1861](https://github.com/ZeldaFan0225/stable_horde/blob/b03d78a/index.ts#L1861)

___

### username

• `Optional` **username**: `string`

The user's unique Username. It is a combination of their chosen alias plus their ID.

#### Inherited from

[UserDetails](UserDetails.md).[username](UserDetails.md#username)

#### Defined in

[index.ts:1867](https://github.com/ZeldaFan0225/stable_horde/blob/b03d78a/index.ts#L1867)

___

### worker\_count

• `Optional` **worker\_count**: `number`

How many workers this user has created (active or inactive)

#### Inherited from

[UserDetails](UserDetails.md).[worker_count](UserDetails.md#worker_count)

#### Defined in

[index.ts:1882](https://github.com/ZeldaFan0225/stable_horde/blob/b03d78a/index.ts#L1882)

___

### worker\_ids

• `Optional` **worker\_ids**: `string`[]

#### Inherited from

[UserDetails](UserDetails.md).[worker_ids](UserDetails.md#worker_ids)

#### Defined in

[index.ts:1883](https://github.com/ZeldaFan0225/stable_horde/blob/b03d78a/index.ts#L1883)

___

### worker\_invited

• `Optional` **worker\_invited**: `number`

Whether this user has been invited to join a worker to the horde and how many of them. When 0, this user cannot add (new) workers to the horde.

#### Inherited from

[UserDetails](UserDetails.md).[worker_invited](UserDetails.md#worker_invited)

#### Defined in

[index.ts:1877](https://github.com/ZeldaFan0225/stable_horde/blob/b03d78a/index.ts#L1877)