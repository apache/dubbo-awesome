# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.014 ops/ms
# Warmup Iteration   2: 2.211 ops/ms
# Warmup Iteration   3: 4.845 ops/ms
Iteration   1: 5.512 ops/ms
Iteration   2: 5.520 ops/ms
Iteration   3: 5.813 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.615 ±(99.9%) 3.126 ops/ms [Average]
  (min, avg, max) = (5.512, 5.615, 5.813), stdev = 0.171
  CI (99.9%): [2.489, 8.741] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:18
# Fork: 1 of 1
# Warmup Iteration   1: 1.399 ops/ms
# Warmup Iteration   2: 4.435 ops/ms
# Warmup Iteration   3: 5.847 ops/ms
Iteration   1: 6.017 ops/ms
Iteration   2: 5.945 ops/ms
Iteration   3: 6.135 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.032 ±(99.9%) 1.750 ops/ms [Average]
  (min, avg, max) = (5.945, 6.032, 6.135), stdev = 0.096
  CI (99.9%): [4.282, 7.782] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:09
# Fork: 1 of 1
# Warmup Iteration   1: 1.481 ops/ms
# Warmup Iteration   2: 4.668 ops/ms
# Warmup Iteration   3: 5.331 ops/ms
Iteration   1: 5.375 ops/ms
Iteration   2: 5.217 ops/ms
Iteration   3: 5.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.380 ±(99.9%) 3.024 ops/ms [Average]
  (min, avg, max) = (5.217, 5.380, 5.548), stdev = 0.166
  CI (99.9%): [2.357, 8.404] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:10:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.358 ops/ms
# Warmup Iteration   2: 3.596 ops/ms
# Warmup Iteration   3: 4.576 ops/ms
Iteration   1: 4.669 ops/ms
Iteration   2: 4.927 ops/ms
Iteration   3: 4.893 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.830 ±(99.9%) 2.554 ops/ms [Average]
  (min, avg, max) = (4.669, 4.830, 4.927), stdev = 0.140
  CI (99.9%): [2.275, 7.384] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:55
# Fork: 1 of 1
# Warmup Iteration   1: 18.876 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 6.378 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 6.085 ±(99.9%) 0.013 ms/op
Iteration   1: 5.539 ±(99.9%) 0.014 ms/op
Iteration   2: 5.702 ±(99.9%) 0.010 ms/op
Iteration   3: 5.725 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.655 ±(99.9%) 1.856 ms/op [Average]
  (min, avg, max) = (5.539, 5.655, 5.725), stdev = 0.102
  CI (99.9%): [3.800, 7.511] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:48
# Fork: 1 of 1
# Warmup Iteration   1: 17.231 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 7.177 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.647 ±(99.9%) 0.012 ms/op
Iteration   1: 5.685 ±(99.9%) 0.007 ms/op
Iteration   2: 5.820 ±(99.9%) 0.010 ms/op
Iteration   3: 5.870 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.791 ±(99.9%) 1.744 ms/op [Average]
  (min, avg, max) = (5.685, 5.791, 5.870), stdev = 0.096
  CI (99.9%): [4.047, 7.536] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:41
# Fork: 1 of 1
# Warmup Iteration   1: 18.369 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 8.146 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.788 ±(99.9%) 0.011 ms/op
Iteration   1: 5.701 ±(99.9%) 0.008 ms/op
Iteration   2: 5.542 ±(99.9%) 0.016 ms/op
Iteration   3: 5.855 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.699 ±(99.9%) 2.849 ms/op [Average]
  (min, avg, max) = (5.542, 5.699, 5.855), stdev = 0.156
  CI (99.9%): [2.850, 8.549] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:34
# Fork: 1 of 1
# Warmup Iteration   1: 19.590 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 9.313 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.638 ±(99.9%) 0.012 ms/op
Iteration   1: 6.973 ±(99.9%) 0.006 ms/op
Iteration   2: 6.680 ±(99.9%) 0.008 ms/op
Iteration   3: 6.526 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.726 ±(99.9%) 4.140 ms/op [Average]
  (min, avg, max) = (6.526, 6.726, 6.973), stdev = 0.227
  CI (99.9%): [2.587, 10.866] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:27
# Fork: 1 of 1
# Warmup Iteration   1: 20.265 ±(99.9%) 0.362 ms/op
# Warmup Iteration   2: 7.831 ±(99.9%) 0.059 ms/op
# Warmup Iteration   3: 6.246 ±(99.9%) 0.029 ms/op
Iteration   1: 5.900 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.819 ms/op
                 createUser·p0.50:   5.546 ms/op
                 createUser·p0.90:   7.152 ms/op
                 createUser·p0.95:   8.602 ms/op
                 createUser·p0.99:   12.517 ms/op
                 createUser·p0.999:  25.573 ms/op
                 createUser·p0.9999: 29.412 ms/op
                 createUser·p1.00:   30.507 ms/op

Iteration   2: 5.673 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   0.496 ms/op
                 createUser·p0.50:   5.341 ms/op
                 createUser·p0.90:   6.816 ms/op
                 createUser·p0.95:   7.782 ms/op
                 createUser·p0.99:   11.354 ms/op
                 createUser·p0.999:  28.726 ms/op
                 createUser·p0.9999: 33.882 ms/op
                 createUser·p1.00:   36.045 ms/op

Iteration   3: 5.984 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.526 ms/op
                 createUser·p0.50:   5.620 ms/op
                 createUser·p0.90:   7.586 ms/op
                 createUser·p0.95:   8.487 ms/op
                 createUser·p0.99:   11.224 ms/op
                 createUser·p0.999:  30.029 ms/op
                 createUser·p0.9999: 34.493 ms/op
                 createUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 163937
  mean =      5.849 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 35452 
    [ 5.000,  7.500) = 115295 
    [ 7.500, 10.000) = 9525 
    [10.000, 12.500) = 2475 
    [12.500, 15.000) = 667 
    [15.000, 17.500) = 235 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 44 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.496 ms/op
     p(50.0000) =      5.489 ms/op
     p(90.0000) =      7.209 ms/op
     p(95.0000) =      8.315 ms/op
     p(99.0000) =     11.731 ms/op
     p(99.9000) =     27.263 ms/op
     p(99.9900) =     33.882 ms/op
     p(99.9990) =     35.123 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 17.153 ±(99.9%) 0.274 ms/op
# Warmup Iteration   2: 6.681 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.756 ±(99.9%) 0.022 ms/op
Iteration   1: 5.609 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.437 ms/op
                 existUser·p0.50:   5.317 ms/op
                 existUser·p0.90:   6.685 ms/op
                 existUser·p0.95:   7.987 ms/op
                 existUser·p0.99:   11.321 ms/op
                 existUser·p0.999:  18.022 ms/op
                 existUser·p0.9999: 27.492 ms/op
                 existUser·p1.00:   28.475 ms/op

Iteration   2: 6.209 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   2.474 ms/op
                 existUser·p0.50:   5.652 ms/op
                 existUser·p0.90:   8.225 ms/op
                 existUser·p0.95:   10.011 ms/op
                 existUser·p0.99:   14.434 ms/op
                 existUser·p0.999:  31.688 ms/op
                 existUser·p0.9999: 36.360 ms/op
                 existUser·p1.00:   37.028 ms/op

Iteration   3: 5.988 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   2.666 ms/op
                 existUser·p0.50:   5.554 ms/op
                 existUser·p0.90:   7.725 ms/op
                 existUser·p0.95:   9.110 ms/op
                 existUser·p0.99:   13.107 ms/op
                 existUser·p0.999:  20.578 ms/op
                 existUser·p0.9999: 34.820 ms/op
                 existUser·p1.00:   36.635 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 161889
  mean =      5.925 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 34973 
    [ 5.000,  7.500) = 110658 
    [ 7.500, 10.000) = 10964 
    [10.000, 12.500) = 3210 
    [12.500, 15.000) = 1287 
    [15.000, 17.500) = 414 
    [17.500, 20.000) = 175 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 51 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      2.437 ms/op
     p(50.0000) =      5.489 ms/op
     p(90.0000) =      7.512 ms/op
     p(95.0000) =      9.028 ms/op
     p(99.0000) =     13.156 ms/op
     p(99.9000) =     21.153 ms/op
     p(99.9900) =     35.483 ms/op
     p(99.9990) =     36.947 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 20.745 ±(99.9%) 0.315 ms/op
# Warmup Iteration   2: 7.333 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 6.145 ±(99.9%) 0.025 ms/op
Iteration   1: 5.775 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.688 ms/op
                 getUser·p0.50:   5.415 ms/op
                 getUser·p0.90:   7.184 ms/op
                 getUser·p0.95:   8.225 ms/op
                 getUser·p0.99:   11.256 ms/op
                 getUser·p0.999:  16.624 ms/op
                 getUser·p0.9999: 27.817 ms/op
                 getUser·p1.00:   28.082 ms/op

Iteration   2: 6.028 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   2.380 ms/op
                 getUser·p0.50:   5.472 ms/op
                 getUser·p0.90:   8.012 ms/op
                 getUser·p0.95:   9.667 ms/op
                 getUser·p0.99:   14.420 ms/op
                 getUser·p0.999:  27.099 ms/op
                 getUser·p0.9999: 38.646 ms/op
                 getUser·p1.00:   39.059 ms/op

Iteration   3: 5.860 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.322 ms/op
                 getUser·p0.50:   5.530 ms/op
                 getUser·p0.90:   7.184 ms/op
                 getUser·p0.95:   8.339 ms/op
                 getUser·p0.99:   12.042 ms/op
                 getUser·p0.999:  26.673 ms/op
                 getUser·p0.9999: 31.031 ms/op
                 getUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 163080
  mean =      5.886 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 38192 
    [ 5.000,  7.500) = 110012 
    [ 7.500, 10.000) = 10511 
    [10.000, 12.500) = 2589 
    [12.500, 15.000) = 1030 
    [15.000, 17.500) = 399 
    [17.500, 20.000) = 154 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.688 ms/op
     p(50.0000) =      5.472 ms/op
     p(90.0000) =      7.356 ms/op
     p(95.0000) =      8.847 ms/op
     p(99.0000) =     12.730 ms/op
     p(99.9000) =     25.360 ms/op
     p(99.9900) =     36.766 ms/op
     p(99.9990) =     38.935 ms/op
     p(99.9999) =     39.059 ms/op
    p(100.0000) =     39.059 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 22.509 ±(99.9%) 0.388 ms/op
# Warmup Iteration   2: 8.841 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 7.101 ±(99.9%) 0.034 ms/op
Iteration   1: 6.794 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   3.289 ms/op
                 listUser·p0.50:   6.398 ms/op
                 listUser·p0.90:   8.126 ms/op
                 listUser·p0.95:   9.470 ms/op
                 listUser·p0.99:   14.287 ms/op
                 listUser·p0.999:  28.859 ms/op
                 listUser·p0.9999: 36.785 ms/op
                 listUser·p1.00:   37.618 ms/op

Iteration   2: 6.967 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.757 ms/op
                 listUser·p0.50:   6.586 ms/op
                 listUser·p0.90:   8.356 ms/op
                 listUser·p0.95:   9.748 ms/op
                 listUser·p0.99:   13.500 ms/op
                 listUser·p0.999:  30.608 ms/op
                 listUser·p0.9999: 33.843 ms/op
                 listUser·p1.00:   34.275 ms/op

Iteration   3: 6.741 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.458 ms/op
                 listUser·p0.50:   6.332 ms/op
                 listUser·p0.90:   8.159 ms/op
                 listUser·p0.95:   9.322 ms/op
                 listUser·p0.99:   13.042 ms/op
                 listUser·p0.999:  27.787 ms/op
                 listUser·p0.9999: 35.586 ms/op
                 listUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 140476
  mean =      6.833 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 2683 
    [ 5.000,  7.500) = 113634 
    [ 7.500, 10.000) = 18386 
    [10.000, 12.500) = 3723 
    [12.500, 15.000) = 1248 
    [15.000, 17.500) = 342 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 86 
    [30.000, 32.500) = 63 
    [32.500, 35.000) = 43 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      2.458 ms/op
     p(50.0000) =      6.447 ms/op
     p(90.0000) =      8.217 ms/op
     p(95.0000) =      9.535 ms/op
     p(99.0000) =     13.550 ms/op
     p(99.9000) =     29.327 ms/op
     p(99.9900) =     35.714 ms/op
     p(99.9990) =     37.485 ms/op
     p(99.9999) =     37.618 ms/op
    p(100.0000) =     37.618 ms/op


# Run complete. Total time: 00:13:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.615 ± 3.126  ops/ms
ClientPb.existUser                       thrpt       3   6.032 ± 1.750  ops/ms
ClientPb.getUser                         thrpt       3   5.380 ± 3.024  ops/ms
ClientPb.listUser                        thrpt       3   4.830 ± 2.554  ops/ms
ClientPb.createUser                       avgt       3   5.655 ± 1.856   ms/op
ClientPb.existUser                        avgt       3   5.791 ± 1.744   ms/op
ClientPb.getUser                          avgt       3   5.699 ± 2.849   ms/op
ClientPb.listUser                         avgt       3   6.726 ± 4.140   ms/op
ClientPb.createUser                     sample  163937   5.849 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.496           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.489           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.209           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.315           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.731           ms/op
ClientPb.createUser:createUser·p0.999   sample          27.263           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.882           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.045           ms/op
ClientPb.existUser                      sample  161889   5.925 ± 0.015   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.437           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.489           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.512           ms/op
ClientPb.existUser:existUser·p0.95      sample           9.028           ms/op
ClientPb.existUser:existUser·p0.99      sample          13.156           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.153           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.483           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.028           ms/op
ClientPb.getUser                        sample  163080   5.886 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.688           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.472           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.356           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.847           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.730           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.360           ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.766           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.059           ms/op
ClientPb.listUser                       sample  140476   6.833 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.458           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.447           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.217           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.535           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.550           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.327           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.714           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.618           ms/op
