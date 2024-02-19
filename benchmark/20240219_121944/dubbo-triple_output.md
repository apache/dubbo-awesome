# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.400 ops/ms
# Warmup Iteration   2: 12.066 ops/ms
# Warmup Iteration   3: 12.239 ops/ms
Iteration   1: 12.434 ops/ms
Iteration   2: 12.570 ops/ms
Iteration   3: 12.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.539 ±(99.9%) 1.714 ops/ms [Average]
  (min, avg, max) = (12.434, 12.539, 12.614), stdev = 0.094
  CI (99.9%): [10.826, 14.253] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.774 ops/ms
# Warmup Iteration   2: 12.835 ops/ms
# Warmup Iteration   3: 12.898 ops/ms
Iteration   1: 12.970 ops/ms
Iteration   2: 12.882 ops/ms
Iteration   3: 13.041 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.964 ±(99.9%) 1.452 ops/ms [Average]
  (min, avg, max) = (12.882, 12.964, 13.041), stdev = 0.080
  CI (99.9%): [11.512, 14.416] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.244 ops/ms
# Warmup Iteration   2: 12.553 ops/ms
# Warmup Iteration   3: 12.938 ops/ms
Iteration   1: 12.764 ops/ms
Iteration   2: 12.913 ops/ms
Iteration   3: 12.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.866 ±(99.9%) 1.606 ops/ms [Average]
  (min, avg, max) = (12.764, 12.866, 12.920), stdev = 0.088
  CI (99.9%): [11.260, 14.472] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.485 ops/ms
# Warmup Iteration   2: 10.320 ops/ms
# Warmup Iteration   3: 10.634 ops/ms
Iteration   1: 10.719 ops/ms
Iteration   2: 10.690 ops/ms
Iteration   3: 10.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.731 ±(99.9%) 0.891 ops/ms [Average]
  (min, avg, max) = (10.690, 10.731, 10.785), stdev = 0.049
  CI (99.9%): [9.840, 11.622] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.211 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.549 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.004 ms/op
Iteration   1: 2.508 ±(99.9%) 0.003 ms/op
Iteration   2: 2.511 ±(99.9%) 0.004 ms/op
Iteration   3: 2.504 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.508 ±(99.9%) 0.057 ms/op [Average]
  (min, avg, max) = (2.504, 2.508, 2.511), stdev = 0.003
  CI (99.9%): [2.451, 2.565] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.664 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.428 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.388 ±(99.9%) 0.005 ms/op
Iteration   1: 2.384 ±(99.9%) 0.007 ms/op
Iteration   2: 2.343 ±(99.9%) 0.005 ms/op
Iteration   3: 2.298 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.342 ±(99.9%) 0.789 ms/op [Average]
  (min, avg, max) = (2.298, 2.342, 2.384), stdev = 0.043
  CI (99.9%): [1.552, 3.131] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.799 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.548 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.454 ±(99.9%) 0.007 ms/op
Iteration   1: 2.461 ±(99.9%) 0.004 ms/op
Iteration   2: 2.465 ±(99.9%) 0.005 ms/op
Iteration   3: 2.443 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.456 ±(99.9%) 0.215 ms/op [Average]
  (min, avg, max) = (2.443, 2.456, 2.465), stdev = 0.012
  CI (99.9%): [2.241, 2.671] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.616 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.996 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.006 ms/op
Iteration   1: 2.952 ±(99.9%) 0.007 ms/op
Iteration   2: 2.910 ±(99.9%) 0.007 ms/op
Iteration   3: 2.958 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.940 ±(99.9%) 0.473 ms/op [Average]
  (min, avg, max) = (2.910, 2.940, 2.958), stdev = 0.026
  CI (99.9%): [2.467, 3.413] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.371 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.598 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.006 ms/op
Iteration   1: 2.496 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   2.421 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.351 ms/op
                 createUser·p0.99:   4.129 ms/op
                 createUser·p0.999:  11.581 ms/op
                 createUser·p0.9999: 13.667 ms/op
                 createUser·p1.00:   17.465 ms/op

Iteration   2: 2.507 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.901 ms/op
                 createUser·p0.50:   2.458 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   3.916 ms/op
                 createUser·p0.999:  9.486 ms/op
                 createUser·p0.9999: 13.210 ms/op
                 createUser·p1.00:   13.812 ms/op

Iteration   3: 2.544 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.899 ms/op
                 createUser·p0.50:   2.499 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.318 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  9.023 ms/op
                 createUser·p0.9999: 12.333 ms/op
                 createUser·p1.00:   16.138 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381251
  mean =      2.515 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 116 
    [ 1.250,  2.500) = 199169 
    [ 2.500,  3.750) = 174835 
    [ 3.750,  5.000) = 6035 
    [ 5.000,  6.250) = 518 
    [ 6.250,  7.500) = 135 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 122 
    [12.500, 13.750) = 112 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      2.454 ms/op
     p(90.0000) =      3.117 ms/op
     p(95.0000) =      3.310 ms/op
     p(99.0000) =      4.076 ms/op
     p(99.9000) =      9.216 ms/op
     p(99.9900) =     13.203 ms/op
     p(99.9990) =     14.408 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.717 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.416 ±(99.9%) 0.005 ms/op
Iteration   1: 2.438 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.790 ms/op
                 existUser·p0.50:   2.388 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.748 ms/op
                 existUser·p0.999:  6.927 ms/op
                 existUser·p0.9999: 13.884 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   2: 2.435 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.525 ms/op
                 existUser·p0.50:   2.363 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.981 ms/op
                 existUser·p0.999:  6.273 ms/op
                 existUser·p0.9999: 13.515 ms/op
                 existUser·p1.00:   14.615 ms/op

Iteration   3: 2.416 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.774 ms/op
                 existUser·p0.50:   2.318 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.834 ms/op
                 existUser·p0.999:  6.982 ms/op
                 existUser·p0.9999: 13.072 ms/op
                 existUser·p1.00:   13.828 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394724
  mean =      2.430 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 156 
    [ 1.250,  2.500) = 217875 
    [ 2.500,  3.750) = 172028 
    [ 3.750,  5.000) = 3739 
    [ 5.000,  6.250) = 501 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 141 
    [12.500, 13.750) = 122 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.525 ms/op
     p(50.0000) =      2.351 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.857 ms/op
     p(99.9000) =      6.606 ms/op
     p(99.9900) =     13.525 ms/op
     p(99.9990) =     14.186 ms/op
     p(99.9999) =     14.615 ms/op
    p(100.0000) =     14.615 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.087 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.583 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.006 ms/op
Iteration   1: 2.518 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   2.445 ms/op
                 getUser·p0.90:   3.129 ms/op
                 getUser·p0.95:   3.318 ms/op
                 getUser·p0.99:   4.076 ms/op
                 getUser·p0.999:  11.295 ms/op
                 getUser·p0.9999: 13.784 ms/op
                 getUser·p1.00:   14.877 ms/op

Iteration   2: 2.550 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.782 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   3.211 ms/op
                 getUser·p0.95:   3.482 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  10.136 ms/op
                 getUser·p0.9999: 12.492 ms/op
                 getUser·p1.00:   13.681 ms/op

Iteration   3: 2.476 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.657 ms/op
                 getUser·p0.50:   2.400 ms/op
                 getUser·p0.90:   3.138 ms/op
                 getUser·p0.95:   3.371 ms/op
                 getUser·p0.99:   4.133 ms/op
                 getUser·p0.999:  8.312 ms/op
                 getUser·p0.9999: 12.026 ms/op
                 getUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381443
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 161 
    [ 1.250,  2.500) = 203924 
    [ 2.500,  3.750) = 168315 
    [ 3.750,  5.000) = 8053 
    [ 5.000,  6.250) = 547 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 118 
    [11.250, 12.500) = 144 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      2.429 ms/op
     p(90.0000) =      3.158 ms/op
     p(95.0000) =      3.391 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      9.104 ms/op
     p(99.9900) =     12.908 ms/op
     p(99.9990) =     14.355 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.968 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.008 ms/op
Iteration   1: 3.010 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.916 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.365 ms/op
                 listUser·p0.9999: 12.032 ms/op
                 listUser·p1.00:   13.042 ms/op

Iteration   2: 2.973 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.942 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.390 ms/op
                 listUser·p0.999:  9.216 ms/op
                 listUser·p0.9999: 10.609 ms/op
                 listUser·p1.00:   11.321 ms/op

Iteration   3: 2.973 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.948 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.902 ms/op
                 listUser·p0.9999: 16.590 ms/op
                 listUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321258
  mean =      2.985 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 156 
    [ 1.250,  2.500) = 96205 
    [ 2.500,  3.750) = 187493 
    [ 3.750,  5.000) = 30814 
    [ 5.000,  6.250) = 5361 
    [ 6.250,  7.500) = 494 
    [ 7.500,  8.750) = 231 
    [ 8.750, 10.000) = 286 
    [10.000, 11.250) = 141 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =      9.498 ms/op
     p(99.9900) =     12.380 ms/op
     p(99.9990) =     17.924 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.539 ± 1.714  ops/ms
ClientPb.existUser                       thrpt       3  12.964 ± 1.452  ops/ms
ClientPb.getUser                         thrpt       3  12.866 ± 1.606  ops/ms
ClientPb.listUser                        thrpt       3  10.731 ± 0.891  ops/ms
ClientPb.createUser                       avgt       3   2.508 ± 0.057   ms/op
ClientPb.existUser                        avgt       3   2.342 ± 0.789   ms/op
ClientPb.getUser                          avgt       3   2.456 ± 0.215   ms/op
ClientPb.listUser                         avgt       3   2.940 ± 0.473   ms/op
ClientPb.createUser                     sample  381251   2.515 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.899           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.454           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.310           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.076           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.216           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.203           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.465           ms/op
ClientPb.existUser                      sample  394724   2.430 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.525           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.351           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.857           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.606           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.525           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.615           ms/op
ClientPb.getUser                        sample  381443   2.514 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.657           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.429           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.391           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.202           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.104           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.908           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.877           ms/op
ClientPb.listUser                       sample  321258   2.985 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.916           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.498           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.380           ms/op
ClientPb.listUser:listUser·p1.00        sample          18.088           ms/op
