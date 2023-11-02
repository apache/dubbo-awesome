# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.341 ops/ms
# Warmup Iteration   2: 3.769 ops/ms
# Warmup Iteration   3: 6.395 ops/ms
Iteration   1: 6.122 ops/ms
Iteration   2: 6.677 ops/ms
Iteration   3: 6.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.484 ±(99.9%) 5.726 ops/ms [Average]
  (min, avg, max) = (6.122, 6.484, 6.677), stdev = 0.314
  CI (99.9%): [0.758, 12.210] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.049 ops/ms
# Warmup Iteration   2: 6.018 ops/ms
# Warmup Iteration   3: 6.557 ops/ms
Iteration   1: 6.731 ops/ms
Iteration   2: 6.237 ops/ms
Iteration   3: 6.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.571 ±(99.9%) 5.280 ops/ms [Average]
  (min, avg, max) = (6.237, 6.571, 6.744), stdev = 0.289
  CI (99.9%): [1.291, 11.850] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.677 ops/ms
# Warmup Iteration   2: 5.786 ops/ms
# Warmup Iteration   3: 6.215 ops/ms
Iteration   1: 6.591 ops/ms
Iteration   2: 6.131 ops/ms
Iteration   3: 6.645 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.455 ±(99.9%) 5.152 ops/ms [Average]
  (min, avg, max) = (6.131, 6.455, 6.645), stdev = 0.282
  CI (99.9%): [1.303, 11.608] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.949 ops/ms
# Warmup Iteration   2: 4.786 ops/ms
# Warmup Iteration   3: 5.339 ops/ms
Iteration   1: 5.274 ops/ms
Iteration   2: 5.551 ops/ms
Iteration   3: 5.686 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.503 ±(99.9%) 3.833 ops/ms [Average]
  (min, avg, max) = (5.274, 5.503, 5.686), stdev = 0.210
  CI (99.9%): [1.670, 9.336] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 14.969 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 5.741 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.232 ±(99.9%) 0.005 ms/op
Iteration   1: 5.037 ±(99.9%) 0.007 ms/op
Iteration   2: 5.217 ±(99.9%) 0.007 ms/op
Iteration   3: 5.003 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.086 ±(99.9%) 2.101 ms/op [Average]
  (min, avg, max) = (5.003, 5.086, 5.217), stdev = 0.115
  CI (99.9%): [2.985, 7.187] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 15.583 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.314 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.948 ±(99.9%) 0.006 ms/op
Iteration   1: 4.965 ±(99.9%) 0.006 ms/op
Iteration   2: 4.861 ±(99.9%) 0.007 ms/op
Iteration   3: 5.114 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.980 ±(99.9%) 2.322 ms/op [Average]
  (min, avg, max) = (4.861, 4.980, 5.114), stdev = 0.127
  CI (99.9%): [2.658, 7.303] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 13.978 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 5.292 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.808 ±(99.9%) 0.008 ms/op
Iteration   1: 4.841 ±(99.9%) 0.009 ms/op
Iteration   2: 5.081 ±(99.9%) 0.007 ms/op
Iteration   3: 4.908 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.943 ±(99.9%) 2.257 ms/op [Average]
  (min, avg, max) = (4.841, 4.943, 5.081), stdev = 0.124
  CI (99.9%): [2.686, 7.200] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.900 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.392 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.916 ±(99.9%) 0.021 ms/op
Iteration   1: 5.796 ±(99.9%) 0.010 ms/op
Iteration   2: 5.975 ±(99.9%) 0.013 ms/op
Iteration   3: 5.747 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.839 ±(99.9%) 2.184 ms/op [Average]
  (min, avg, max) = (5.747, 5.839, 5.975), stdev = 0.120
  CI (99.9%): [3.656, 8.023] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.802 ±(99.9%) 0.199 ms/op
# Warmup Iteration   2: 5.766 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.249 ±(99.9%) 0.020 ms/op
Iteration   1: 5.202 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.208 ms/op
                 createUser·p0.50:   5.005 ms/op
                 createUser·p0.90:   6.463 ms/op
                 createUser·p0.95:   7.045 ms/op
                 createUser·p0.99:   8.925 ms/op
                 createUser·p0.999:  21.711 ms/op
                 createUser·p0.9999: 28.705 ms/op
                 createUser·p1.00:   31.752 ms/op

Iteration   2: 5.139 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.241 ms/op
                 createUser·p0.50:   4.776 ms/op
                 createUser·p0.90:   6.472 ms/op
                 createUser·p0.95:   7.143 ms/op
                 createUser·p0.99:   8.765 ms/op
                 createUser·p0.999:  21.999 ms/op
                 createUser·p0.9999: 25.053 ms/op
                 createUser·p1.00:   25.592 ms/op

Iteration   3: 5.102 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.232 ms/op
                 createUser·p0.50:   4.891 ms/op
                 createUser·p0.90:   6.201 ms/op
                 createUser·p0.95:   6.865 ms/op
                 createUser·p0.99:   8.880 ms/op
                 createUser·p0.999:  22.122 ms/op
                 createUser·p0.9999: 27.918 ms/op
                 createUser·p1.00:   29.458 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 186267
  mean =      5.148 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 100760 
    [ 5.000,  7.500) = 79316 
    [ 7.500, 10.000) = 5197 
    [10.000, 12.500) = 458 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.208 ms/op
     p(50.0000) =      4.899 ms/op
     p(90.0000) =      6.390 ms/op
     p(95.0000) =      7.037 ms/op
     p(99.0000) =      8.864 ms/op
     p(99.9000) =     21.758 ms/op
     p(99.9900) =     28.467 ms/op
     p(99.9990) =     29.773 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.948 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 5.694 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.940 ±(99.9%) 0.016 ms/op
Iteration   1: 5.064 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.690 ms/op
                 existUser·p0.50:   4.784 ms/op
                 existUser·p0.90:   6.283 ms/op
                 existUser·p0.95:   7.217 ms/op
                 existUser·p0.99:   9.830 ms/op
                 existUser·p0.999:  20.606 ms/op
                 existUser·p0.9999: 24.906 ms/op
                 existUser·p1.00:   30.867 ms/op

Iteration   2: 4.854 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.909 ms/op
                 existUser·p0.50:   4.579 ms/op
                 existUser·p0.90:   5.947 ms/op
                 existUser·p0.95:   6.906 ms/op
                 existUser·p0.99:   10.076 ms/op
                 existUser·p0.999:  15.025 ms/op
                 existUser·p0.9999: 24.459 ms/op
                 existUser·p1.00:   25.035 ms/op

Iteration   3: 4.665 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.954 ms/op
                 existUser·p0.50:   4.391 ms/op
                 existUser·p0.90:   5.734 ms/op
                 existUser·p0.95:   6.799 ms/op
                 existUser·p0.99:   8.815 ms/op
                 existUser·p0.999:  18.346 ms/op
                 existUser·p0.9999: 27.623 ms/op
                 existUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 197667
  mean =      4.856 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 136769 
    [ 5.000,  7.500) = 53888 
    [ 7.500, 10.000) = 5334 
    [10.000, 12.500) = 1151 
    [12.500, 15.000) = 172 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.690 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      6.021 ms/op
     p(95.0000) =      6.955 ms/op
     p(99.0000) =      9.535 ms/op
     p(99.9000) =     19.868 ms/op
     p(99.9900) =     25.877 ms/op
     p(99.9990) =     29.107 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 15.529 ±(99.9%) 0.226 ms/op
# Warmup Iteration   2: 5.753 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.096 ±(99.9%) 0.018 ms/op
Iteration   1: 5.176 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.081 ms/op
                 getUser·p0.50:   4.866 ms/op
                 getUser·p0.90:   6.431 ms/op
                 getUser·p0.95:   7.586 ms/op
                 getUser·p0.99:   11.354 ms/op
                 getUser·p0.999:  21.104 ms/op
                 getUser·p0.9999: 28.217 ms/op
                 getUser·p1.00:   30.409 ms/op

Iteration   2: 5.392 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.527 ms/op
                 getUser·p0.50:   5.095 ms/op
                 getUser·p0.90:   6.758 ms/op
                 getUser·p0.95:   7.528 ms/op
                 getUser·p0.99:   10.781 ms/op
                 getUser·p0.999:  24.010 ms/op
                 getUser·p0.9999: 31.520 ms/op
                 getUser·p1.00:   33.292 ms/op

Iteration   3: 5.007 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.898 ms/op
                 getUser·p0.50:   4.809 ms/op
                 getUser·p0.90:   6.005 ms/op
                 getUser·p0.95:   6.808 ms/op
                 getUser·p0.99:   9.191 ms/op
                 getUser·p0.999:  25.287 ms/op
                 getUser·p0.9999: 32.107 ms/op
                 getUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 184936
  mean =      5.187 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 100294 
    [ 5.000,  7.500) = 76286 
    [ 7.500, 10.000) = 6150 
    [10.000, 12.500) = 1257 
    [12.500, 15.000) = 510 
    [15.000, 17.500) = 180 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.898 ms/op
     p(50.0000) =      4.915 ms/op
     p(90.0000) =      6.447 ms/op
     p(95.0000) =      7.348 ms/op
     p(99.0000) =     10.387 ms/op
     p(99.9000) =     22.546 ms/op
     p(99.9900) =     31.376 ms/op
     p(99.9990) =     33.070 ms/op
     p(99.9999) =     33.292 ms/op
    p(100.0000) =     33.292 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.121 ±(99.9%) 0.297 ms/op
# Warmup Iteration   2: 6.472 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.958 ±(99.9%) 0.024 ms/op
Iteration   1: 6.053 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.839 ms/op
                 listUser·p0.50:   5.628 ms/op
                 listUser·p0.90:   7.643 ms/op
                 listUser·p0.95:   8.798 ms/op
                 listUser·p0.99:   11.928 ms/op
                 listUser·p0.999:  24.942 ms/op
                 listUser·p0.9999: 32.660 ms/op
                 listUser·p1.00:   34.734 ms/op

Iteration   2: 6.202 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.669 ms/op
                 listUser·p0.50:   5.792 ms/op
                 listUser·p0.90:   7.619 ms/op
                 listUser·p0.95:   8.667 ms/op
                 listUser·p0.99:   11.764 ms/op
                 listUser·p0.999:  27.492 ms/op
                 listUser·p0.9999: 34.966 ms/op
                 listUser·p1.00:   35.717 ms/op

Iteration   3: 6.022 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.777 ms/op
                 listUser·p0.50:   5.743 ms/op
                 listUser·p0.90:   7.062 ms/op
                 listUser·p0.95:   8.200 ms/op
                 listUser·p0.99:   12.009 ms/op
                 listUser·p0.999:  23.429 ms/op
                 listUser·p0.9999: 27.822 ms/op
                 listUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 157484
  mean =      6.091 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 20844 
    [ 5.000,  7.500) = 121339 
    [ 7.500, 10.000) = 11347 
    [10.000, 12.500) = 2752 
    [12.500, 15.000) = 567 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 109 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.669 ms/op
     p(50.0000) =      5.726 ms/op
     p(90.0000) =      7.463 ms/op
     p(95.0000) =      8.602 ms/op
     p(99.0000) =     11.862 ms/op
     p(99.9000) =     26.133 ms/op
     p(99.9900) =     33.260 ms/op
     p(99.9990) =     35.642 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.484 ± 5.726  ops/ms
ClientPb.existUser                       thrpt       3   6.571 ± 5.280  ops/ms
ClientPb.getUser                         thrpt       3   6.455 ± 5.152  ops/ms
ClientPb.listUser                        thrpt       3   5.503 ± 3.833  ops/ms
ClientPb.createUser                       avgt       3   5.086 ± 2.101   ms/op
ClientPb.existUser                        avgt       3   4.980 ± 2.322   ms/op
ClientPb.getUser                          avgt       3   4.943 ± 2.257   ms/op
ClientPb.listUser                         avgt       3   5.839 ± 2.184   ms/op
ClientPb.createUser                     sample  186267   5.148 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.208           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.899           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.390           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.037           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.864           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.758           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.467           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.752           ms/op
ClientPb.existUser                      sample  197667   4.856 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.690           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.579           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.021           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.955           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.535           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.868           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.877           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.867           ms/op
ClientPb.getUser                        sample  184936   5.187 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.898           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.915           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.447           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.348           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.387           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.546           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.376           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.292           ms/op
ClientPb.listUser                       sample  157484   6.091 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.669           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.726           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.463           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.602           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.862           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.133           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.260           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.717           ms/op
