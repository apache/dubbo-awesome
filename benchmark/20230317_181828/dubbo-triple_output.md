# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.219 ops/ms
# Warmup Iteration   2: 6.152 ops/ms
# Warmup Iteration   3: 8.611 ops/ms
Iteration   1: 8.871 ops/ms
Iteration   2: 9.303 ops/ms
Iteration   3: 9.541 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.238 ±(99.9%) 6.193 ops/ms [Average]
  (min, avg, max) = (8.871, 9.238, 9.541), stdev = 0.339
  CI (99.9%): [3.045, 15.431] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.813 ops/ms
# Warmup Iteration   2: 8.956 ops/ms
# Warmup Iteration   3: 9.774 ops/ms
Iteration   1: 10.194 ops/ms
Iteration   2: 9.747 ops/ms
Iteration   3: 9.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.807 ±(99.9%) 6.577 ops/ms [Average]
  (min, avg, max) = (9.480, 9.807, 10.194), stdev = 0.360
  CI (99.9%): [3.230, 16.384] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.852 ops/ms
# Warmup Iteration   2: 8.423 ops/ms
# Warmup Iteration   3: 9.519 ops/ms
Iteration   1: 9.451 ops/ms
Iteration   2: 9.746 ops/ms
Iteration   3: 9.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.628 ±(99.9%) 2.845 ops/ms [Average]
  (min, avg, max) = (9.451, 9.628, 9.746), stdev = 0.156
  CI (99.9%): [6.783, 12.474] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.127 ops/ms
# Warmup Iteration   2: 7.338 ops/ms
# Warmup Iteration   3: 8.090 ops/ms
Iteration   1: 8.359 ops/ms
Iteration   2: 8.192 ops/ms
Iteration   3: 8.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.257 ±(99.9%) 1.632 ops/ms [Average]
  (min, avg, max) = (8.192, 8.257, 8.359), stdev = 0.089
  CI (99.9%): [6.625, 9.889] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.373 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.712 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.650 ±(99.9%) 0.004 ms/op
Iteration   1: 3.355 ±(99.9%) 0.009 ms/op
Iteration   2: 3.405 ±(99.9%) 0.009 ms/op
Iteration   3: 3.337 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.365 ±(99.9%) 0.641 ms/op [Average]
  (min, avg, max) = (3.337, 3.365, 3.405), stdev = 0.035
  CI (99.9%): [2.725, 4.006] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.955 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.467 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.007 ms/op
Iteration   1: 3.207 ±(99.9%) 0.008 ms/op
Iteration   2: 3.125 ±(99.9%) 0.009 ms/op
Iteration   3: 3.199 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.177 ±(99.9%) 0.828 ms/op [Average]
  (min, avg, max) = (3.125, 3.177, 3.207), stdev = 0.045
  CI (99.9%): [2.349, 4.005] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.394 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.604 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.501 ±(99.9%) 0.005 ms/op
Iteration   1: 3.411 ±(99.9%) 0.004 ms/op
Iteration   2: 3.290 ±(99.9%) 0.008 ms/op
Iteration   3: 3.312 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.338 ±(99.9%) 1.172 ms/op [Average]
  (min, avg, max) = (3.290, 3.338, 3.411), stdev = 0.064
  CI (99.9%): [2.166, 4.509] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.673 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.396 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.174 ±(99.9%) 0.011 ms/op
Iteration   1: 4.067 ±(99.9%) 0.009 ms/op
Iteration   2: 3.894 ±(99.9%) 0.012 ms/op
Iteration   3: 3.929 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.963 ±(99.9%) 1.672 ms/op [Average]
  (min, avg, max) = (3.894, 3.963, 4.067), stdev = 0.092
  CI (99.9%): [2.291, 5.636] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.425 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.808 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.425 ±(99.9%) 0.010 ms/op
Iteration   1: 3.500 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.331 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.076 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  20.497 ms/op
                 createUser·p0.9999: 34.537 ms/op
                 createUser·p1.00:   36.700 ms/op

Iteration   2: 3.413 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.395 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   6.234 ms/op
                 createUser·p0.999:  23.547 ms/op
                 createUser·p0.9999: 26.289 ms/op
                 createUser·p1.00:   27.394 ms/op

Iteration   3: 3.389 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.171 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   6.237 ms/op
                 createUser·p0.999:  22.750 ms/op
                 createUser·p0.9999: 27.112 ms/op
                 createUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279500
  mean =      3.433 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3193 
    [ 2.500,  5.000) = 268976 
    [ 5.000,  7.500) = 6246 
    [ 7.500, 10.000) = 596 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 104 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.144 ms/op
     p(99.9000) =     22.102 ms/op
     p(99.9900) =     32.966 ms/op
     p(99.9990) =     35.450 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.132 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.318 ±(99.9%) 0.010 ms/op
Iteration   1: 3.270 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.468 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   5.844 ms/op
                 existUser·p0.999:  9.593 ms/op
                 existUser·p0.9999: 23.771 ms/op
                 existUser·p1.00:   24.576 ms/op

Iteration   2: 3.318 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.026 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   4.866 ms/op
                 existUser·p0.999:  17.618 ms/op
                 existUser·p0.9999: 26.280 ms/op
                 existUser·p1.00:   26.804 ms/op

Iteration   3: 3.290 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.399 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  12.652 ms/op
                 existUser·p0.9999: 25.372 ms/op
                 existUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291288
  mean =      3.293 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10020 
    [ 2.500,  5.000) = 276636 
    [ 5.000,  7.500) = 4071 
    [ 7.500, 10.000) = 236 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 68 

  Percentiles, ms/op:
      p(0.0000) =      1.026 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     10.158 ms/op
     p(99.9900) =     25.739 ms/op
     p(99.9990) =     26.914 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.943 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.825 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.510 ±(99.9%) 0.011 ms/op
Iteration   1: 3.439 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   6.840 ms/op
                 getUser·p0.999:  21.856 ms/op
                 getUser·p0.9999: 44.918 ms/op
                 getUser·p1.00:   46.072 ms/op

Iteration   2: 3.395 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.628 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   5.136 ms/op
                 getUser·p0.999:  22.479 ms/op
                 getUser·p0.9999: 26.706 ms/op
                 getUser·p1.00:   28.246 ms/op

Iteration   3: 3.430 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.495 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   6.153 ms/op
                 getUser·p0.999:  20.396 ms/op
                 getUser·p0.9999: 28.006 ms/op
                 getUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280402
  mean =      3.421 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 274481 
    [ 5.000, 10.000) = 5490 
    [10.000, 15.000) = 143 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 128 
    [25.000, 30.000) = 128 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.964 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     21.010 ms/op
     p(99.9900) =     42.205 ms/op
     p(99.9990) =     45.823 ms/op
     p(99.9999) =     46.072 ms/op
    p(100.0000) =     46.072 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.301 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 4.388 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.129 ±(99.9%) 0.014 ms/op
Iteration   1: 3.886 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.030 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.052 ms/op
                 listUser·p0.999:  21.507 ms/op
                 listUser·p0.9999: 24.077 ms/op
                 listUser·p1.00:   25.854 ms/op

Iteration   2: 3.924 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   7.520 ms/op
                 listUser·p0.999:  15.590 ms/op
                 listUser·p0.9999: 17.685 ms/op
                 listUser·p1.00:   18.776 ms/op

Iteration   3: 3.873 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.310 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  15.106 ms/op
                 listUser·p0.9999: 19.313 ms/op
                 listUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 246510
  mean =      3.894 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 239269 
    [ 5.000,  7.500) = 5450 
    [ 7.500, 10.000) = 893 
    [10.000, 12.500) = 308 
    [12.500, 15.000) = 187 
    [15.000, 17.500) = 162 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.030 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     16.081 ms/op
     p(99.9900) =     22.982 ms/op
     p(99.9990) =     24.644 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.238 ± 6.193  ops/ms
ClientPb.existUser                       thrpt       3   9.807 ± 6.577  ops/ms
ClientPb.getUser                         thrpt       3   9.628 ± 2.845  ops/ms
ClientPb.listUser                        thrpt       3   8.257 ± 1.632  ops/ms
ClientPb.createUser                       avgt       3   3.365 ± 0.641   ms/op
ClientPb.existUser                        avgt       3   3.177 ± 0.828   ms/op
ClientPb.getUser                          avgt       3   3.338 ± 1.172   ms/op
ClientPb.listUser                         avgt       3   3.963 ± 1.672   ms/op
ClientPb.createUser                     sample  279500   3.433 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.171           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.273           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.940           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.235           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.144           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.102           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.966           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.700           ms/op
ClientPb.existUser                      sample  291288   3.293 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.026           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.203           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.977           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.571           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.158           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.739           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.099           ms/op
ClientPb.getUser                        sample  280402   3.421 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.964           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.330           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.789           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.116           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.078           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.010           ms/op
ClientPb.getUser:getUser·p0.9999        sample          42.205           ms/op
ClientPb.getUser:getUser·p1.00          sample          46.072           ms/op
ClientPb.listUser                       sample  246510   3.894 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.030           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.777           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.243           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.898           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.081           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.982           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.854           ms/op
