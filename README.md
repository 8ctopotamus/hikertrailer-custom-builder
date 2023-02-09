# 🚛 HikerTrailer Custom Builder
A custom trailer builder.

* [Current Spreadsheet]('./assets/configurator.xlsx)
* [Wireframe PSD](./assets/wireframe.psd)

## Initial Questions
* Does this need to integrate with Shopify or Woocommerce? Currently there is a Shopify site.

## Roadmap 🛣

We'll build an awesome, fast UI using a JS Framework, such as [React](https://reactjs.org/).

Something like this (TBD):

<img title="wireframe" alt="wireframe" src="./assets/wireframe.jpg" />

### Tech Options

* Wordpress backend**
  
  😄 PROS
  
  * Easily embed anywhere on the site
  * Would allow for close integration with WP/WooCommerce
  * Baked-in user accounts and Schemas
  * Already have infustructure (WPEngine)
  
  ☹ CONS

  * Not as nice dev experience (No version control, which makes code collaboration hard)
  * Harder to maintain

* **MERN** (Mongo/Express/React/Node)

  😄 PROS

  * Total control of everything, fully customizable
  * Would be separate, fullstack app
  * More choices of DB
  * Much better dev experience (This one is for us 😁), easier to maintain (to me, at least)

  ☹ CONS

  * Would need to develop DB, Schemas, Authentication ourselves
  * Would need new infrastructure/services (Heroku/Mongo Atlas)

---

### Phase 1
* [ ] Custom UI
  * [ ] Stepper on left with Quote info on right
* [ ] Generate the various reports out of user input data
* [ ] Send all of this data somewhere
  * Quick Option: Could dump data into email
  * Longer: drop it into a Google Sheet or DB
* [ ] Wrap UI in WP plugin 
  * (if we're planning on embedding this in the WP site)

### Phase 2
* [ ] Decide on final Backend/DB - 
  * could use WP as a backend - depends how closely they want to integrate this build with WP
  * Super custom Express/
* [ ] User Accounts
* [ ] User can save multiple configurations

### Phase 3
* [ ] 3D Models
* [ ] Integrate 3D Models into UI

---