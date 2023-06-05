# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.074 ops/ms
# Warmup Iteration   2: 6.077 ops/ms
# Warmup Iteration   3: 8.075 ops/ms
Iteration   1: 9.005 ops/ms
Iteration   2: 9.248 ops/ms
Iteration   3: 9.396 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.216 ±(99.9%) 3.601 ops/ms [Average]
  (min, avg, max) = (9.005, 9.216, 9.396), stdev = 0.197
  CI (99.9%): [5.615, 12.817] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 2.903 ops/ms
# Warmup Iteration   2: 8.642 ops/ms
# Warmup Iteration   3: 9.613 ops/ms
Iteration   1: 9.722 ops/ms
Iteration   2: 9.885 ops/ms
Iteration   3: 9.382 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.663 ±(99.9%) 4.677 ops/ms [Average]
  (min, avg, max) = (9.382, 9.663, 9.885), stdev = 0.256
  CI (99.9%): [4.987, 14.340] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.791 ops/ms
# Warmup Iteration   2: 8.496 ops/ms
# Warmup Iteration   3: 8.893 ops/ms
Iteration   1: 9.257 ops/ms
Iteration   2: 9.273 ops/ms
Iteration   3: 8.979 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.170 ±(99.9%) 3.019 ops/ms [Average]
  (min, avg, max) = (8.979, 9.170, 9.273), stdev = 0.165
  CI (99.9%): [6.150, 12.189] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.010 ops/ms
# Warmup Iteration   2: 7.039 ops/ms
# Warmup Iteration   3: 7.948 ops/ms
Iteration   1: 7.978 ops/ms
Iteration   2: 7.912 ops/ms
Iteration   3: 7.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.954 ±(99.9%) 0.677 ops/ms [Average]
  (min, avg, max) = (7.912, 7.954, 7.978), stdev = 0.037
  CI (99.9%): [7.278, 8.631] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.070 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.863 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.628 ±(99.9%) 0.004 ms/op
Iteration   1: 3.330 ±(99.9%) 0.013 ms/op
Iteration   2: 3.641 ±(99.9%) 0.005 ms/op
Iteration   3: 3.586 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.519 ±(99.9%) 3.031 ms/op [Average]
  (min, avg, max) = (3.330, 3.519, 3.641), stdev = 0.166
  CI (99.9%): [0.488, 6.550] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.840 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.816 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.207 ±(99.9%) 0.004 ms/op
Iteration   1: 3.318 ±(99.9%) 0.005 ms/op
Iteration   2: 3.222 ±(99.9%) 0.009 ms/op
Iteration   3: 3.509 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.350 ±(99.9%) 2.663 ms/op [Average]
  (min, avg, max) = (3.222, 3.350, 3.509), stdev = 0.146
  CI (99.9%): [0.687, 6.012] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.321 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.787 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.497 ±(99.9%) 0.006 ms/op
Iteration   1: 3.489 ±(99.9%) 0.008 ms/op
Iteration   2: 3.375 ±(99.9%) 0.006 ms/op
Iteration   3: 3.364 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.409 ±(99.9%) 1.265 ms/op [Average]
  (min, avg, max) = (3.364, 3.409, 3.489), stdev = 0.069
  CI (99.9%): [2.144, 4.674] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.260 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.279 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.101 ±(99.9%) 0.010 ms/op
Iteration   1: 3.988 ±(99.9%) 0.010 ms/op
Iteration   2: 3.954 ±(99.9%) 0.008 ms/op
Iteration   3: 3.981 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.974 ±(99.9%) 0.330 ms/op [Average]
  (min, avg, max) = (3.954, 3.974, 3.988), stdev = 0.018
  CI (99.9%): [3.644, 4.304] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.718 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.993 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.488 ±(99.9%) 0.010 ms/op
Iteration   1: 3.361 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.757 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  21.940 ms/op
                 createUser·p0.9999: 24.686 ms/op
                 createUser·p1.00:   25.362 ms/op

Iteration   2: 3.406 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   6.357 ms/op
                 createUser·p0.999:  22.267 ms/op
                 createUser·p0.9999: 26.375 ms/op
                 createUser·p1.00:   27.230 ms/op

Iteration   3: 3.509 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   5.939 ms/op
                 createUser·p0.999:  24.773 ms/op
                 createUser·p0.9999: 35.513 ms/op
                 createUser·p1.00:   36.635 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280201
  mean =      3.424 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10718 
    [ 2.500,  5.000) = 263391 
    [ 5.000,  7.500) = 4766 
    [ 7.500, 10.000) = 703 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 182 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 40 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     23.095 ms/op
     p(99.9900) =     34.275 ms/op
     p(99.9990) =     36.438 ms/op
     p(99.9999) =     36.635 ms/op
    p(100.0000) =     36.635 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.499 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.646 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.307 ±(99.9%) 0.007 ms/op
Iteration   1: 3.239 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.368 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  10.977 ms/op
                 existUser·p0.9999: 23.204 ms/op
                 existUser·p1.00:   24.904 ms/op

Iteration   2: 3.245 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.761 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   5.915 ms/op
                 existUser·p0.999:  12.796 ms/op
                 existUser·p0.9999: 31.140 ms/op
                 existUser·p1.00:   32.932 ms/op

Iteration   3: 3.383 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.708 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.883 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   6.210 ms/op
                 existUser·p0.999:  10.631 ms/op
                 existUser·p0.9999: 26.920 ms/op
                 existUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291853
  mean =      3.288 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8204 
    [ 2.500,  5.000) = 277615 
    [ 5.000,  7.500) = 4830 
    [ 7.500, 10.000) = 838 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.368 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     11.144 ms/op
     p(99.9900) =     29.381 ms/op
     p(99.9990) =     32.640 ms/op
     p(99.9999) =     32.932 ms/op
    p(100.0000) =     32.932 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.517 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.780 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.459 ±(99.9%) 0.011 ms/op
Iteration   1: 3.466 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.827 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   4.002 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   6.414 ms/op
                 getUser·p0.999:  22.468 ms/op
                 getUser·p0.9999: 31.835 ms/op
                 getUser·p1.00:   32.899 ms/op

Iteration   2: 3.424 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.395 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   5.751 ms/op
                 getUser·p0.999:  10.398 ms/op
                 getUser·p0.9999: 26.531 ms/op
                 getUser·p1.00:   26.837 ms/op

Iteration   3: 3.407 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.370 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   5.538 ms/op
                 getUser·p0.999:  21.091 ms/op
                 getUser·p0.9999: 29.118 ms/op
                 getUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279559
  mean =      3.432 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8507 
    [ 2.500,  5.000) = 264439 
    [ 5.000,  7.500) = 5611 
    [ 7.500, 10.000) = 599 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     12.433 ms/op
     p(99.9900) =     30.736 ms/op
     p(99.9990) =     32.350 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.461 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.636 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.204 ±(99.9%) 0.014 ms/op
Iteration   1: 4.064 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.855 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   8.038 ms/op
                 listUser·p0.999:  22.194 ms/op
                 listUser·p0.9999: 32.056 ms/op
                 listUser·p1.00:   32.866 ms/op

Iteration   2: 3.972 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.845 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  15.647 ms/op
                 listUser·p0.9999: 17.353 ms/op
                 listUser·p1.00:   18.612 ms/op

Iteration   3: 4.024 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.130 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  18.466 ms/op
                 listUser·p0.9999: 22.643 ms/op
                 listUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238636
  mean =      4.020 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 228341 
    [ 5.000,  7.500) = 7747 
    [ 7.500, 10.000) = 1620 
    [10.000, 12.500) = 239 
    [12.500, 15.000) = 220 
    [15.000, 17.500) = 174 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      7.569 ms/op
     p(99.9000) =     17.498 ms/op
     p(99.9900) =     30.577 ms/op
     p(99.9990) =     32.506 ms/op
     p(99.9999) =     32.866 ms/op
    p(100.0000) =     32.866 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.216 ± 3.601  ops/ms
ClientPb.existUser                       thrpt       3   9.663 ± 4.677  ops/ms
ClientPb.getUser                         thrpt       3   9.170 ± 3.019  ops/ms
ClientPb.listUser                        thrpt       3   7.954 ± 0.677  ops/ms
ClientPb.createUser                       avgt       3   3.519 ± 3.031   ms/op
ClientPb.existUser                        avgt       3   3.350 ± 2.663   ms/op
ClientPb.getUser                          avgt       3   3.409 ± 1.265   ms/op
ClientPb.listUser                         avgt       3   3.974 ± 0.330   ms/op
ClientPb.createUser                     sample  280201   3.424 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.775           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.326           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.813           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.906           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.095           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.275           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.635           ms/op
ClientPb.existUser                      sample  291853   3.288 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.368           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.174           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.924           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.005           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.144           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.381           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.932           ms/op
ClientPb.getUser                        sample  279559   3.432 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.370           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.351           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.153           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.816           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.433           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.736           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.899           ms/op
ClientPb.listUser                       sample  238636   4.020 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.855           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.858           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.569           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.498           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.577           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.866           ms/op
