<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dynamics 365 ERP System</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
        }

        .container {
            display: flex;
            min-height: 100vh;
        }

        .sidebar {
            width: 250px;
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border-right: 1px solid rgba(255, 255, 255, 0.2);
            padding: 20px;
            transition: all 0.3s ease;
        }

        .logo {
            text-align: center;
            margin-bottom: 30px;
            color: white;
            font-size: 24px;
            font-weight: bold;
        }

        .nav-item {
            padding: 12px 15px;
            margin: 5px 0;
            border-radius: 10px;
            cursor: pointer;
            transition: all 0.3s ease;
            color: rgba(255, 255, 255, 0.8);
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .nav-item:hover, .nav-item.active {
            background: rgba(255, 255, 255, 0.2);
            color: white;
            transform: translateX(5px);
        }

        .main-content {
            flex: 1;
            padding: 20px;
            overflow-y: auto;
        }

        .header {
            background: rgba(255, 255, 255, 0.95);
            padding: 20px;
            border-radius: 15px;
            margin-bottom: 20px;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.1);
            backdrop-filter: blur(10px);
        }

        .header h1 {
            color: #333;
            margin-bottom: 10px;
        }

        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-bottom: 30px;
        }

        .stat-card {
            background: rgba(255, 255, 255, 0.95);
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.1);
            backdrop-filter: blur(10px);
            transition: transform 0.3s ease;
        }

        .stat-card:hover {
            transform: translateY(-5px);
        }

        .stat-number {
            font-size: 2.5em;
            font-weight: bold;
            color: #667eea;
            margin-bottom: 10px;
        }

        .stat-label {
            color: #666;
            font-size: 1.1em;
        }

        .content-section {
            background: rgba(255, 255, 255, 0.95);
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.1);
            backdrop-filter: blur(10px);
            display: none;
        }

        .content-section.active {
            display: block;
            animation: fadeIn 0.5s ease;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .btn {
            padding: 12px 24px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            font-size: 14px;
            font-weight: 600;
            transition: all 0.3s ease;
            text-decoration: none;
            display: inline-flex;
            align-items: center;
            gap: 8px;
        }

        .btn-primary {
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
        }

        .btn-primary:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(102, 126, 234, 0.4);
        }

        .btn-success {
            background: linear-gradient(135deg, #56ab2f, #a8e6cf);
            color: white;
        }

        .btn-danger {
            background: linear-gradient(135deg, #ff416c, #ff4b2b);
            color: white;
        }

        .btn-warning {
            background: linear-gradient(135deg, #f093fb, #f5576c);
            color: white;
        }

        .form-group {
            margin-bottom: 20px;
        }

        .form-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: 600;
            color: #333;
        }

        .form-control {
            width: 100%;
            padding: 12px;
            border: 2px solid #e1e5e9;
            border-radius: 8px;
            font-size: 14px;
            transition: border-color 0.3s ease;
        }

        .form-control:focus {
            outline: none;
            border-color: #667eea;
            box-shadow: 0 0 0 3px rgba(102, 126, 234, 0.1);
        }

        .table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
        }

        .table th {
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
            padding: 15px;
            text-align: left;
            font-weight: 600;
        }

        .table td {
            padding: 15px;
            border-bottom: 1px solid #e1e5e9;
        }

        .table tr:hover {
            background: rgba(102, 126, 234, 0.05);
        }

        .modal {
            display: none;
            position: fixed;
            z-index: 1000;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.5);
            backdrop-filter: blur(5px);
        }

        .modal-content {
            background: white;
            margin: 5% auto;
            padding: 30px;
            border-radius: 15px;
            width: 90%;
            max-width: 600px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            animation: modalSlideIn 0.3s ease;
        }

        @keyframes modalSlideIn {
            from { transform: translateY(-50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }

        .close {
            color: #aaa;
            float: right;
            font-size: 28px;
            font-weight: bold;
            cursor: pointer;
            transition: color 0.3s ease;
        }

        .close:hover {
            color: #333;
        }

        .search-bar {
            margin-bottom: 20px;
        }

        .search-bar input {
            width: 300px;
            padding: 12px;
            border: 2px solid #e1e5e9;
            border-radius: 25px;
            font-size: 14px;
        }

        .action-buttons {
            display: flex;
            gap: 10px;
        }

        .status-badge {
            padding: 4px 12px;
            border-radius: 20px;
            font-size: 12px;
            font-weight: 600;
        }

        .status-active {
            background: #d4edda;
            color: #155724;
        }

        .status-inactive {
            background: #f8d7da;
            color: #721c24;
        }

        .status-pending {
            background: #fff3cd;
            color: #856404;
        }

        .dashboard-grid {
            display: grid;
            grid-template-columns: 2fr 1fr;
            gap: 20px;
            margin-top: 20px;
        }

        .recent-activities {
            background: white;
            border-radius: 15px;
            padding: 20px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
        }

        .activity-item {
            display: flex;
            align-items: center;
            padding: 10px 0;
            border-bottom: 1px solid #e1e5e9;
        }

        .activity-icon {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background: linear-gradient(135deg, #667eea, #764ba2);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            margin-right: 15px;
        }

        .chart-container {
            background: white;
            border-radius: 15px;
            padding: 20px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            height: 300px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #666;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="sidebar">
            <div class="logo">
                <div>💼 Dynamics 365</div>
            </div>
            <div class="nav-item active" onclick="showSection('dashboard')">
                📊 Dashboard
            </div>
            <div class="nav-item" onclick="showSection('customers')">
                👥 Pelanggan
            </div>
            <div class="nav-item" onclick="showSection('products')">
                📦 Produk
            </div>
            <div class="nav-item" onclick="showSection('orders')">
                🛒 Pesanan
            </div>
            <div class="nav-item" onclick="showSection('finance')">
                💰 Keuangan
            </div>
            <div class="nav-item" onclick="showSection('inventory')">
                📋 Inventori
            </div>
            <div class="nav-item" onclick="showSection('reports')">
                📈 Laporan
            </div>
        </div>

        <div class="main-content">
            <!-- Dashboard Section -->
            <div id="dashboard" class="content-section active">
                <div class="header">
                    <h1>Dashboard</h1>
                    <p>Selamat datang di sistem ERP Dynamics 365</p>
                </div>

                <div class="stats-grid">
                    <div class="stat-card">
                        <div class="stat-number">1,234</div>
                        <div class="stat-label">Total Pelanggan</div>
                    </div>
                    <div class="stat-card">
                        <div class="stat-number">567</div>
                        <div class="stat-label">Produk Aktif</div>
                    </div>
                    <div class="stat-card">
                        <div class="stat-number">89</div>
                        <div class="stat-label">Pesanan Bulan Ini</div>
                    </div>
                    <div class="stat-card">
                        <div class="stat-number">Rp 45.6M</div>
                        <div class="stat-label">Pendapatan</div>
                    </div>
                </div>

                <div class="dashboard-grid">
                    <div class="recent-activities">
                        <h3>Aktivitas Terbaru</h3>
                        <div class="activity-item">
                            <div class="activity-icon">👤</div>
                            <div>
                                <strong>Pelanggan baru terdaftar</strong><br>
                                <small>PT. Maju Bersama - 2 jam lalu</small>
                            </div>
                        </div>
                        <div class="activity-item">
                            <div class="activity-icon">🛒</div>
                            <div>
                                <strong>Pesanan baru diterima</strong><br>
                                <small>Order #12345 - Rp 2.5M - 4 jam lalu</small>
                            </div>
                        </div>
                        <div class="activity-item">
                            <div class="activity-icon">💰</div>
                            <div>
                                <strong>Pembayaran diterima</strong><br>
                                <small>Invoice #INV-001 - Rp 1.8M - 6 jam lalu</small>
                            </div>
                        </div>
                    </div>
                    <div class="chart-container">
                        <div>📊 Grafik Penjualan<br><small>Fitur grafik akan ditampilkan di sini</small></div>
                    </div>
                </div>
            </div>

            <!-- Customers Section -->
            <div id="customers" class="content-section">
                <div class="header">
                    <h1>Manajemen Pelanggan</h1>
                    <button class="btn btn-primary" onclick="openModal('customerModal')">+ Tambah Pelanggan</button>
                </div>

                <div class="search-bar">
                    <input type="text" placeholder="Cari pelanggan..." onkeyup="searchTable('customersTable', this.value)">
                </div>

                <table class="table" id="customersTable">
                    <thead>
                        <tr>
                            <th>ID</th>
                            <th>Nama</th>
                            <th>Email</th>
                            <th>Telepon</th>
                            <th>Status</th>
                            <th>Aksi</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>001</td>
                            <td>PT. Maju Bersama</td>
                            <td>info@majubersama.com</td>
                            <td>021-12345678</td>
                            <td><span class="status-badge status-active">Aktif</span></td>
                            <td class="action-buttons">
                                <button class="btn btn-warning" onclick="editCustomer(1)">Edit</button>
                                <button class="btn btn-danger" onclick="deleteCustomer(1)">Hapus</button>
                            </td>
                        </tr>
                        <tr>
                            <td>002</td>
                            <td>CV. Sukses Mandiri</td>
                            <td>admin@suksesmandiri.co.id</td>
                            <td>022-87654321</td>
                            <td><span class="status-badge status-active">Aktif</span></td>
                            <td class="action-buttons">
                                <button class="btn btn-warning" onclick="editCustomer(2)">Edit</button>
                                <button class="btn btn-danger" onclick="deleteCustomer(2)">Hapus</button>
                            </td>
                        </tr>
                        <tr>
                            <td>003</td>
                            <td>Toko Berkah Jaya</td>
                            <td>berkah@gmail.com</td>
                            <td>081234567890</td>
                            <td><span class="status-badge status-inactive">Tidak Aktif</span></td>
                            <td class="action-buttons">
                                <button class="btn btn-warning" onclick="editCustomer(3)">Edit</button>
                                <button class="btn btn-danger" onclick="deleteCustomer(3)">Hapus</button>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </div>

            <!-- Products Section -->
            <div id="products" class="content-section">
                <div class="header">
                    <h1>Manajemen Produk</h1>
                    <button class="btn btn-primary" onclick="openModal('productModal')">+ Tambah Produk</button>
                </div>

                <div class="search-bar">
                    <input type="text" placeholder="Cari produk..." onkeyup="searchTable('productsTable', this.value)">
                </div>

                <table class="table" id="productsTable">
                    <thead>
                        <tr>
                            <th>Kode</th>
                            <th>Nama Produk</th>
                            <th>Kategori</th>
                            <th>Harga</th>
                            <th>Stok</th>
                            <th>Status</th>
                            <th>Aksi</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>PRD001</td>
                            <td>Laptop Gaming ROG</td>
                            <td>Elektronik</td>
                            <td>Rp 25.000.000</td>
                            <td>15</td>
                            <td><span class="status-badge status-active">Tersedia</span></td>
                            <td class="action-buttons">
                                <button class="btn btn-warning" onclick="editProduct(1)">Edit</button>
                                <button class="btn btn-danger" onclick="deleteProduct(1)">Hapus</button>
                            </td>
                        </tr>
                        <tr>
                            <td>PRD002</td>
                            <td>Mouse Wireless Logitech</td>
                            <td>Aksesoris</td>
                            <td>Rp 450.000</td>
                            <td>50</td>
                            <td><span class="status-badge status-active">Tersedia</span></td>
                            <td class="action-buttons">
                                <button class="btn btn-warning" onclick="editProduct(2)">Edit</button>
                                <button class="btn btn-danger" onclick="deleteProduct(2)">Hapus</button>
                            </td>
                        </tr>
                        <tr>
                            <td>PRD003</td>
                            <td>Keyboard Mechanical</td>
                            <td>Aksesoris</td>
                            <td>Rp 1.200.000</td>
                            <td>0</td>
                            <td><span class="status-badge status-inactive">Habis</span></td>
                            <td class="action-buttons">
                                <button class="btn btn-warning" onclick="editProduct(3)">Edit</button>
                                <button class="btn btn-danger" onclick="deleteProduct(3)">Hapus</button>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </div>

            <!-- Orders Section -->
            <div id="orders" class="content-section">
                <div class="header">
                    <h1>Manajemen Pesanan</h1>
                    <button class="btn btn-primary" onclick="openModal('orderModal')">+ Tambah Pesanan</button>
                </div>

                <div class="search-bar">
                    <input type="text" placeholder="Cari pesanan..." onkeyup="searchTable('ordersTable', this.value)">
                </div>

                <table class="table" id="ordersTable">
                    <thead>
                        <tr>
                            <th>No. Order</th>
                            <th>Pelanggan</th>
                            <th>Tanggal</th>
                            <th>Total</th>
                            <th>Status</th>
                            <th>Aksi</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>ORD001</td>
                            <td>PT. Maju Bersama</td>
                            <td>2024-08-01</td>
                            <td>Rp 25.450.000</td>
                            <td><span class="status-badge status-pending">Proses</span></td>
                            <td class="action-buttons">
                                <button class="btn btn-warning" onclick="editOrder(1)">Edit</button>
                                <button class="btn btn-danger" onclick="deleteOrder(1)">Hapus</button>
                            </td>
                        </tr>
                        <tr>
                            <td>ORD002</td>
                            <td>CV. Sukses Mandiri</td>
                            <td>2024-08-02</td>
                            <td>Rp 1.650.000</td>
                            <td><span class="status-badge status-active">Selesai</span></td>
                            <td class="action-buttons">
                                <button class="btn btn-warning" onclick="editOrder(2)">Edit</button>
                                <button class="btn btn-danger" onclick="deleteOrder(2)">Hapus</button>
                            </td>
                        </tr>
                        <tr>
                            <td>ORD003</td>
                            <td>Toko Berkah Jaya</td>
                            <td>2024-08-03</td>
                            <td>Rp 2.700.000</td>
                            <td><span class="status-badge status-pending">Pending</span></td>
                            <td class="action-buttons">
                                <button class="btn btn-warning" onclick="editOrder(3)">Edit</button>
                                <button class="btn btn-danger" onclick="deleteOrder(3)">Hapus</button>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </div>

            <!-- Finance Section -->
            <div id="finance" class="content-section">
                <div class="header">
                    <h1>Manajemen Keuangan</h1>
                    <button class="btn btn-primary" onclick="openModal('financeModal')">+ Tambah Transaksi</button>
                </div>

                <div class="stats-grid" style="margin-bottom: 30px;">
                    <div class="stat-card">
                        <div class="stat-number">Rp 125.5M</div>
                        <div class="stat-label">Total Pendapatan</div>
                    </div>
                    <div class="stat-card">
                        <div class="stat-number">Rp 85.2M</div>
                        <div class="stat-label">Total Pengeluaran</div>
                    </div>
                    <div class="stat-card">
                        <div class="stat-number">Rp 40.3M</div>
                        <div class="stat-label">Laba Bersih</div>
                    </div>
                </div>

                <table class="table">
                    <thead>
                        <tr>
                            <th>ID Transaksi</th>
                            <th>Tanggal</th>
                            <th>Deskripsi</th>
                            <th>Tipe</th>
                            <th>Jumlah</th>
                            <th>Aksi</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>TRX001</td>
                            <td>2024-08-01</td>
                            <td>Penjualan Laptop</td>
                            <td><span class="status-badge status-active">Masuk</span></td>
                            <td>+ Rp 25.000.000</td>
                            <td class="action-buttons">
                                <button class="btn btn-warning" onclick="editFinance(1)">Edit</button>
                                <button class="btn btn-danger" onclick="deleteFinance(1)">Hapus</button>
                            </td>
                        </tr>
                        <tr>
                            <td>TRX002</td>
                            <td>2024-08-02</td>
                            <td>Pembelian Stok</td>
                            <td><span class="status-badge status-inactive">Keluar</span></td>
                            <td>- Rp 15.000.000</td>
                            <td class="action-buttons">
                                <button class="btn btn-warning" onclick="editFinance(2)">Edit</button>
                                <button class="btn btn-danger" onclick="deleteFinance(2)">Hapus</button>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </div>

            <!-- Inventory Section -->
            <div id="inventory" class="content-section">
                <div class="header">
                    <h1>Manajemen Inventori</h1>
                    <button class="btn btn-primary" onclick="openModal('inventoryModal')">+ Tambah Stok</button>
                </div>

                <table class="table">
                    <thead>
                        <tr>
                            <th>Kode Produk</th>
                            <th>Nama Produk</th>
                            <th>Stok Saat Ini</th>
                            <th>Stok Minimum</th>
                            <th>Lokasi</th>
                            <th>Status</th>
                            <th>Aksi</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>PRD001</td>
                            <td>Laptop Gaming ROG</td>
                            <td>15</td>
                            <td>5</td>
                            <td>Gudang A</td>
                            <td><span class="status-badge status-active">Normal</span></td>
                            <td class="action-buttons">
                                <button class="btn btn-warning" onclick="editInventory(1)">Edit</button>
                                <button class="btn btn-danger" onclick="deleteInventory(1)">Hapus</button>
                            </td>
                        </tr>
                        <tr>
                            <td>PRD002</td>
                            <td>Mouse Wireless</td>
                            <td>3</td>
                            <td>10</td>
                            <td>Gudang B</td>
                            <td><span class="status-badge status-pending">Rendah</span></td>
                            <td class="action-buttons">
                                <button class="btn btn-warning" onclick="editInventory(2)">Edit</button>
                                <button class="btn btn-danger" onclick="deleteInventory(2)">Hapus</button>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </div>

            <!-- Reports Section -->
            <div id="reports" class="content-section">
                <div class="header">
                    <h1>Laporan</h1>
                    <button class="btn btn-primary" onclick="generateReport()">Generate Laporan</button>
                </div>

                <div class="stats-grid">
                    <div class="stat-card">
                        <h3>Laporan Penjualan</h3>
                        <p>Periode: Agustus 2024</p>
                        <button class="btn btn-success">Download PDF</button>
                    </div>
                    <div class="stat-card">
                        <h3>Laporan Keuangan</h3>
                        <p>Laba Rugi Bulanan</p>
                        <button class="btn btn-success">Download Excel</button>
                    </div>
                    <div class="stat-card">
                        <h3>Laporan Inventori</h3>
                        <p>Stok dan Pergerakan</p>
                        <button class="btn btn-success">Download CSV</button>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Customer Modal -->
    <div id="customerModal" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('customerModal')">&times;</span>
            <h2>Tambah/Edit Pelanggan</h2>
            <form onsubmit="saveCustomer(event)">
                <div class="form-group">
                    <label>Nama Perusahaan/Pelanggan</label>
                    <input type="text" class="form-control" id="customerName" required>
                </div>
                <div class="form-group">
                    <label>Email</label>
                    <input type="email" class="form-control" id="customerEmail" required>
                </div>
                <div class="form-group">
                    <label>Telepon</label>
                    <input type="tel" class="form-control" id="customerPhone" required>
                </div>
                <div class="form-group">
                    <label>Alamat</label>
                    <textarea class="form-control" id="customerAddress" rows="3"></textarea>
                </div>
                <div class="form-group">
                    <label>Status</label>
                    <select class="form-control" id="customerStatus">
                        <option value="active">Aktif</option>
                        <option value="inactive">Tidak Aktif</option>
                    </select>
                </div>
                <button type="submit" class="btn btn-primary">Simpan</button>
                <button type="button" class="btn btn-danger" onclick="closeModal('customerModal')">Batal</button>
            </form>
        </div>
    </div>

    <!-- Product Modal -->
    <div id="productModal" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('productModal')">&times;</span>
            <h2>Tambah/Edit Produk</h2>
            <form onsubmit="saveProduct(event)">
                <div class="form-group">
                    <label>Kode Produk</label>
                    <input type="text" class="form-control" id="productCode" required>
                </div>
                <div class="form-group">
                    <label>Nama Produk</label>
                    <input type="text" class="form-control" id="productName" required>
                </div>
                <div class="form-group">
                    <label>Kategori</label>
                    <select class="form-control" id="productCategory">
                        <option value="elektronik">Elektronik</option>
                        <option value="aksesoris">Aksesoris</option>
                        <option value="furniture">Furniture</option>
                        <option value="pakaian">Pakaian</option>
                    </select>
                </div>
                <div class="form-group">
                    <label>Harga</label>
                    <input type="number" class="form-control" id="productPrice" required>
                </div>
                <div class="form-group">
                    <label>Stok Awal</label>
                    <input type="number" class="form-control" id="productStock" required>
                </div>
                <div class="form-group">
                    <label>Deskripsi</label>
                    <textarea class="form-control" id="productDescription" rows="3"></textarea>
                </div>
                <button type="submit" class="btn btn-primary">Simpan</button>
                <button type="button" class="btn btn-danger" onclick="closeModal('productModal')">Batal</button>
            </form>
        </div>
    </div>

    <!-- Order Modal -->
    <div id="orderModal" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('orderModal')">&times;</span>
            <h2>Tambah/Edit Pesanan</h2>
            <form onsubmit="saveOrder(event)">
                <div class="form-group">
                    <label>No. Order</label>
                    <input type="text" class="form-control" id="orderNumber" required>
                </div>
                <div class="form-group">
                    <label>Pelanggan</label>
                    <select class="form-control" id="orderCustomer">
                        <option value="1">PT. Maju Bersama</option>
                        <option value="2">CV. Sukses Mandiri</option>
                        <option value="3">Toko Berkah Jaya</option>
                    </select>
                </div>
                <div class="form-group">
                    <label>Tanggal Order</label>
                    <input type="date" class="form-control" id="orderDate" required>
                </div>
                <div class="form-group">
                    <label>Produk</label>
                    <select class="form-control" id="orderProduct">
                        <option value="1">Laptop Gaming ROG</option>
                        <option value="2">Mouse Wireless Logitech</option>
                        <option value="3">Keyboard Mechanical</option>
                    </select>
                </div>
                <div class="form-group">
                    <label>Jumlah</label>
                    <input type="number" class="form-control" id="orderQuantity" required>
                </div>
                <div class="form-group">
                    <label>Status</label>
                    <select class="form-control" id="orderStatus">
                        <option value="pending">Pending</option>
                        <option value="process">Proses</option>
                        <option value="completed">Selesai</option>
                        <option value="cancelled">Dibatalkan</option>
                    </select>
                </div>
                <button type="submit" class="btn btn-primary">Simpan</button>
                <button type="button" class="btn btn-danger" onclick="closeModal('orderModal')">Batal</button>
            </form>
        </div>
    </div>

    <!-- Finance Modal -->
    <div id="financeModal" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('financeModal')">&times;</span>
            <h2>Tambah/Edit Transaksi Keuangan</h2>
            <form onsubmit="saveFinance(event)">
                <div class="form-group">
                    <label>ID Transaksi</label>
                    <input type="text" class="form-control" id="financeId" required>
                </div>
                <div class="form-group">
                    <label>Tanggal</label>
                    <input type="date" class="form-control" id="financeDate" required>
                </div>
                <div class="form-group">
                    <label>Deskripsi</label>
                    <input type="text" class="form-control" id="financeDescription" required>
                </div>
                <div class="form-group">
                    <label>Tipe Transaksi</label>
                    <select class="form-control" id="financeType">
                        <option value="income">Pemasukan</option>
                        <option value="expense">Pengeluaran</option>
                    </select>
                </div>
                <div class="form-group">
                    <label>Jumlah</label>
                    <input type="number" class="form-control" id="financeAmount" required>
                </div>
                <div class="form-group">
                    <label>Kategori</label>
                    <select class="form-control" id="financeCategory">
                        <option value="sales">Penjualan</option>
                        <option value="purchase">Pembelian</option>
                        <option value="operational">Operasional</option>
                        <option value="marketing">Marketing</option>
                    </select>
                </div>
                <button type="submit" class="btn btn-primary">Simpan</button>
                <button type="button" class="btn btn-danger" onclick="closeModal('financeModal')">Batal</button>
            </form>
        </div>
    </div>

    <!-- Inventory Modal -->
    <div id="inventoryModal" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('inventoryModal')">&times;</span>
            <h2>Tambah/Edit Inventori</h2>
            <form onsubmit="saveInventory(event)">
                <div class="form-group">
                    <label>Produk</label>
                    <select class="form-control" id="inventoryProduct">
                        <option value="1">Laptop Gaming ROG</option>
                        <option value="2">Mouse Wireless Logitech</option>
                        <option value="3">Keyboard Mechanical</option>
                    </select>
                </div>
                <div class="form-group">
                    <label>Stok Saat Ini</label>
                    <input type="number" class="form-control" id="inventoryStock" required>
                </div>
                <div class="form-group">
                    <label>Stok Minimum</label>
                    <input type="number" class="form-control" id="inventoryMinStock" required>
                </div>
                <div class="form-group">
                    <label>Lokasi</label>
                    <select class="form-control" id="inventoryLocation">
                        <option value="gudang-a">Gudang A</option>
                        <option value="gudang-b">Gudang B</option>
                        <option value="gudang-c">Gudang C</option>
                        <option value="showroom">Showroom</option>
                    </select>
                </div>
                <div class="form-group">
                    <label>Catatan</label>
                    <textarea class="form-control" id="inventoryNotes" rows="3"></textarea>
                </div>
                <button type="submit" class="btn btn-primary">Simpan</button>
                <button type="button" class="btn btn-danger" onclick="closeModal('inventoryModal')">Batal</button>
            </form>
        </div>
    </div>

    <script>
        // Global variables
        let customers = [
            {id: 1, name: 'PT. Maju Bersama', email: 'info@majubersama.com', phone: '021-12345678', status: 'active'},
            {id: 2, name: 'CV. Sukses Mandiri', email: 'admin@suksesmandiri.co.id', phone: '022-87654321', status: 'active'},
            {id: 3, name: 'Toko Berkah Jaya', email: 'berkah@gmail.com', phone: '081234567890', status: 'inactive'}
        ];

        let products = [
            {id: 1, code: 'PRD001', name: 'Laptop Gaming ROG', category: 'Elektronik', price: 25000000, stock: 15, status: 'available'},
            {id: 2, code: 'PRD002', name: 'Mouse Wireless Logitech', category: 'Aksesoris', price: 450000, stock: 50, status: 'available'},
            {id: 3, code: 'PRD003', name: 'Keyboard Mechanical', category: 'Aksesoris', price: 1200000, stock: 0, status: 'out_of_stock'}
        ];

        let orders = [
            {id: 1, number: 'ORD001', customer: 'PT. Maju Bersama', date: '2024-08-01', total: 25450000, status: 'process'},
            {id: 2, number: 'ORD002', customer: 'CV. Sukses Mandiri', date: '2024-08-02', total: 1650000, status: 'completed'},
            {id: 3, number: 'ORD003', customer: 'Toko Berkah Jaya', date: '2024-08-03', total: 2700000, status: 'pending'}
        ];

        let currentEditId = null;
        let currentEditType = null;

        // Navigation functions
        function showSection(sectionName) {
            // Hide all sections
            const sections = document.querySelectorAll('.content-section');
            sections.forEach(section => section.classList.remove('active'));
            
            // Show selected section
            document.getElementById(sectionName).classList.add('active');
            
            // Update navigation
            const navItems = document.querySelectorAll('.nav-item');
            navItems.forEach(item => item.classList.remove('active'));
            event.target.classList.add('active');
        }

        // Modal functions
        function openModal(modalId) {
            document.getElementById(modalId).style.display = 'block';
            currentEditId = null;
            currentEditType = modalId.replace('Modal', '');
        }

        function closeModal(modalId) {
            document.getElementById(modalId).style.display = 'none';
            // Reset form
            const form = document.querySelector(`#${modalId} form`);
            if (form) form.reset();
            currentEditId = null;
            currentEditType = null;
        }

        // Search function
        function searchTable(tableId, searchTerm) {
            const table = document.getElementById(tableId);
            const rows = table.getElementsByTagName('tbody')[0].getElementsByTagName('tr');
            
            for (let i = 0; i < rows.length; i++) {
                let found = false;
                const cells = rows[i].getElementsByTagName('td');
                
                for (let j = 0; j < cells.length - 1; j++) { // -1 to exclude action column
                    if (cells[j].textContent.toLowerCase().includes(searchTerm.toLowerCase())) {
                        found = true;
                        break;
                    }
                }
                
                rows[i].style.display = found ? '' : 'none';
            }
        }

        // Customer functions
        function saveCustomer(event) {
            event.preventDefault();
            
            const name = document.getElementById('customerName').value;
            const email = document.getElementById('customerEmail').value;
            const phone = document.getElementById('customerPhone').value;
            const status = document.getElementById('customerStatus').value;
            
            if (currentEditId) {
                // Update existing customer
                const customerIndex = customers.findIndex(c => c.id === currentEditId);
                if (customerIndex !== -1) {
                    customers[customerIndex] = {
                        ...customers[customerIndex],
                        name, email, phone, status
                    };
                }
            } else {
                // Add new customer
                const newId = Math.max(...customers.map(c => c.id)) + 1;
                customers.push({
                    id: newId,
                    name, email, phone, status
                });
            }
            
            refreshCustomersTable();
            closeModal('customerModal');
            showNotification('Data pelanggan berhasil disimpan!', 'success');
        }

        function editCustomer(id) {
            const customer = customers.find(c => c.id === id);
            if (customer) {
                currentEditId = id;
                document.getElementById('customerName').value = customer.name;
                document.getElementById('customerEmail').value = customer.email;
                document.getElementById('customerPhone').value = customer.phone;
                document.getElementById('customerStatus').value = customer.status;
                openModal('customerModal');
            }
        }

        function deleteCustomer(id) {
            if (confirm('Apakah Anda yakin ingin menghapus pelanggan ini?')) {
                customers = customers.filter(c => c.id !== id);
                refreshCustomersTable();
                showNotification('Pelanggan berhasil dihapus!', 'success');
            }
        }

        function refreshCustomersTable() {
            const tbody = document.querySelector('#customersTable tbody');
            tbody.innerHTML = '';
            
            customers.forEach(customer => {
                const statusClass = customer.status === 'active' ? 'status-active' : 'status-inactive';
                const statusText = customer.status === 'active' ? 'Aktif' : 'Tidak Aktif';
                
                tbody.innerHTML += `
                    <tr>
                        <td>${customer.id.toString().padStart(3, '0')}</td>
                        <td>${customer.name}</td>
                        <td>${customer.email}</td>
                        <td>${customer.phone}</td>
                        <td><span class="status-badge ${statusClass}">${statusText}</span></td>
                        <td class="action-buttons">
                            <button class="btn btn-warning" onclick="editCustomer(${customer.id})">Edit</button>
                            <button class="btn btn-danger" onclick="deleteCustomer(${customer.id})">Hapus</button>
                        </td>
                    </tr>
                `;
            });
        }

        // Product functions
        function saveProduct(event) {
            event.preventDefault();
            
            const code = document.getElementById('productCode').value;
            const name = document.getElementById('productName').value;
            const category = document.getElementById('productCategory').value;
            const price = parseInt(document.getElementById('productPrice').value);
            const stock = parseInt(document.getElementById('productStock').value);
            
            if (currentEditId) {
                // Update existing product
                const productIndex = products.findIndex(p => p.id === currentEditId);
                if (productIndex !== -1) {
                    products[productIndex] = {
                        ...products[productIndex],
                        code, name, category, price, stock,
                        status: stock > 0 ? 'available' : 'out_of_stock'
                    };
                }
            } else {
                // Add new product
                const newId = Math.max(...products.map(p => p.id)) + 1;
                products.push({
                    id: newId,
                    code, name, category, price, stock,
                    status: stock > 0 ? 'available' : 'out_of_stock'
                });
            }
            
            refreshProductsTable();
            closeModal('productModal');
            showNotification('Data produk berhasil disimpan!', 'success');
        }

        function editProduct(id) {
            const product = products.find(p => p.id === id);
            if (product) {
                currentEditId = id;
                document.getElementById('productCode').value = product.code;
                document.getElementById('productName').value = product.name;
                document.getElementById('productCategory').value = product.category;
                document.getElementById('productPrice').value = product.price;
                document.getElementById('productStock').value = product.stock;
                openModal('productModal');
            }
        }

        function deleteProduct(id) {
            if (confirm('Apakah Anda yakin ingin menghapus produk ini?')) {
                products = products.filter(p => p.id !== id);
                refreshProductsTable();
                showNotification('Produk berhasil dihapus!', 'success');
            }
        }

        function refreshProductsTable() {
            const tbody = document.querySelector('#productsTable tbody');
            tbody.innerHTML = '';
            
            products.forEach(product => {
                const statusClass = product.status === 'available' ? 'status-active' : 'status-inactive';
                const statusText = product.status === 'available' ? 'Tersedia' : 'Habis';
                
                tbody.innerHTML += `
                    <tr>
                        <td>${product.code}</td>
                        <td>${product.name}</td>
                        <td>${product.category}</td>
                        <td>Rp ${product.price.toLocaleString('id-ID')}</td>
                        <td>${product.stock}</td>
                        <td><span class="status-badge ${statusClass}">${statusText}</span></td>
                        <td class="action-buttons">
                            <button class="btn btn-warning" onclick="editProduct(${product.id})">Edit</button>
                            <button class="btn btn-danger" onclick="deleteProduct(${product.id})">Hapus</button>
                        </td>
                    </tr>
                `;
            });
        }

        // Order functions
        function saveOrder(event) {
            event.preventDefault();
            
            const number = document.getElementById('orderNumber').value;
            const customerId = document.getElementById('orderCustomer').value;
            const customer = customers.find(c => c.id == customerId)?.name || 'Unknown';
            const date = document.getElementById('orderDate').value;
            const quantity = parseInt(document.getElementById('orderQuantity').value);
            const productId = document.getElementById('orderProduct').value;
            const product = products.find(p => p.id == productId);
            const total = product ? product.price * quantity : 0;
            const status = document.getElementById('orderStatus').value;
            
            if (currentEditId) {
                // Update existing order
                const orderIndex = orders.findIndex(o => o.id === currentEditId);
                if (orderIndex !== -1) {
                    orders[orderIndex] = {
                        ...orders[orderIndex],
                        number, customer, date, total, status
                    };
                }
            } else {
                // Add new order
                const newId = Math.max(...orders.map(o => o.id)) + 1;
                orders.push({
                    id: newId,
                    number, customer, date, total, status
                });
            }
            
            refreshOrdersTable();
            closeModal('orderModal');
            showNotification('Data pesanan berhasil disimpan!', 'success');
        }

        function editOrder(id) {
            const order = orders.find(o => o.id === id);
            if (order) {
                currentEditId = id;
                document.getElementById('orderNumber').value = order.number;
                document.getElementById('orderDate').value = order.date;
                document.getElementById('orderStatus').value = order.status;
                openModal('orderModal');
            }
        }

        function deleteOrder(id) {
            if (confirm('Apakah Anda yakin ingin menghapus pesanan ini?')) {
                orders = orders.filter(o => o.id !== id);
                refreshOrdersTable();
                showNotification('Pesanan berhasil dihapus!', 'success');
            }
        }

        function refreshOrdersTable() {
            const tbody = document.querySelector('#ordersTable tbody');
            tbody.innerHTML = '';
            
            orders.forEach(order => {
                let statusClass = 'status-pending';
                let statusText = 'Pending';
                
                if (order.status === 'completed') {
                    statusClass = 'status-active';
                    statusText = 'Selesai';
                } else if (order.status === 'process') {
                    statusClass = 'status-pending';
                    statusText = 'Proses';
                }
                
                tbody.innerHTML += `
                    <tr>
                        <td>${order.number}</td>
                        <td>${order.customer}</td>
                        <td>${order.date}</td>
                        <td>Rp ${order.total.toLocaleString('id-ID')}</td>
                        <td><span class="status-badge ${statusClass}">${statusText}</span></td>
                        <td class="action-buttons">
                            <button class="btn btn-warning" onclick="editOrder(${order.id})">Edit</button>
                            <button class="btn btn-danger" onclick="deleteOrder(${order.id})">Hapus</button>
                        </td>
                    </tr>
                `;
            });
        }

        // Finance functions
        function saveFinance(event) {
            event.preventDefault();
            showNotification('Transaksi keuangan berhasil disimpan!', 'success');
            closeModal('financeModal');
        }

        function editFinance(id) {
            openModal('financeModal');
        }

        function deleteFinance(id) {
            if (confirm('Apakah Anda yakin ingin menghapus transaksi ini?')) {
                showNotification('Transaksi berhasil dihapus!', 'success');
            }
        }

        // Inventory functions
        function saveInventory(event) {
            event.preventDefault();
            showNotification('Data inventori berhasil disimpan!', 'success');
            closeModal('inventoryModal');
        }

        function editInventory(id) {
            openModal('inventoryModal');
        }

        function deleteInventory(id) {
            if (confirm('Apakah Anda yakin ingin menghapus data inventori ini?')) {
                showNotification('Data inventori berhasil dihapus!', 'success');
            }
        }

        // Report functions
        function generateReport() {
            showNotification('Laporan sedang diproses...', 'info');
            setTimeout(() => {
                showNotification('Laporan berhasil dibuat!', 'success');
            }, 2000);
        }

        // Notification function
        function showNotification(message, type = 'info') {
            // Create notification element
            const notification = document.createElement('div');
            notification.style.cssText = `
                position: fixed;
                top: 20px;
                right: 20px;
                padding: 15px 20px;
                border-radius: 8px;
                color: white;
                font-weight: 600;
                z-index: 9999;
                animation: slideIn 0.3s ease;
                max-width: 300px;
            `;
            
            // Set background color based on type
            switch(type) {
                case 'success':
                    notification.style.background = 'linear-gradient(135deg, #56ab2f, #a8e6cf)';
                    break;
                case 'error':
                    notification.style.background = 'linear-gradient(135deg, #ff416c, #ff4b2b)';
                    break;
                case 'warning':
                    notification.style.background = 'linear-gradient(135deg, #f093fb, #f5576c)';
                    break;
                default:
                    notification.style.background = 'linear-gradient(135deg, #667eea, #764ba2)';
            }
            
            notification.textContent = message;
            document.body.appendChild(notification);
            
            // Remove notification after 3 seconds
            setTimeout(() => {
                notification.style.animation = 'slideOut 0.3s ease';
                setTimeout(() => {
                    document.body.removeChild(notification);
                }, 300);
            }, 3000);
        }

        // Add CSS for notification animations
        const style = document.createElement('style');
        style.textContent = `
            @keyframes slideIn {
                from { transform: translateX(100%); opacity: 0; }
                to { transform: translateX(0); opacity: 1; }
            }
            @keyframes slideOut {
                from { transform: translateX(0); opacity: 1; }
                to { transform: translateX(100%); opacity: 0; }
            }
        `;
        document.head.appendChild(style);

        // Close modals when clicking outside
        window.onclick = function(event) {
            const modals = document.querySelectorAll('.modal');
            modals.forEach(modal => {
                if (event.target === modal) {
                    modal.style.display = 'none';
                }
            });
        }

        // Initialize the application
        document.addEventListener('DOMContentLoaded', function() {
            // Set default date to today for date inputs
            const today = new Date().toISOString().split('T')[0];
            const dateInputs = document.querySelectorAll('input[type="date"]');
            dateInputs.forEach(input => {
                if (!input.value) {
                    input.value = today;
                }
            });

            // Show welcome notification
            setTimeout(() => {
                showNotification('Selamat datang di Dynamics 365 ERP System!', 'success');
            }, 1000);
        });
    </script>
</body>
</html>