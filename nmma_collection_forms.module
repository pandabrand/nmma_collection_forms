<?php

function nmma_search_form($form, &$form_state) {
  // action
  $form['#action'] = url('combined/');

  // search field.
  $form['name'] = array(
    '#title' => t('Search'),
    '#type' => 'textfield',
    '#attributes' => array(
      'placeholder' => t('Discover by Artist Name, Title, or Keyword')
    ),
    '#required' => TRUE,
  );

  $form['submit_button'] = array(
    '#type' => 'submit',
    '#value' => t('Search'),
  );

  return $form;
}