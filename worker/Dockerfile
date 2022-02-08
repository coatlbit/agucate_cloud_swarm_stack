ARG FRAPPE_BRANCH=develop
FROM frappe/erpnext-worker:${FRAPPE_BRANCH}

RUN install_app posawesome https://github.com/yrestom/POS-Awesome master && \
  install_app frappe_s3_attachment https://github.com/zerodha/frappe-attachments-s3 master && \
  install_app metabase_integration https://github.com/pipech/frappe-metabase master && \
  install_app bookings https://github.com/franknyarkoh/bookings master && \
  install_app bench_manager https://github.com/frappe/bench_manager develop && \
  install_app aguacate_theme  https://aguacate-codes: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@github.com/aguacate-codes/aguacate_theme.git beta && \
  install_app school https://github.com/frappe/school version-13 && \
  install_app hospitality https://github.com/frappe/hospitality develop && \
  install_app wiki https://github.com/frappe/wiki version-13 && \
  install_app aguacate_healthcare https://aguacate-codes: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@github.com/aguacate-codes/aguacate_healthcare.git version-13
