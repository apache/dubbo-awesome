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
# Warmup Iteration   1: 1.741 ops/ms
# Warmup Iteration   2: 4.534 ops/ms
# Warmup Iteration   3: 7.331 ops/ms
Iteration   1: 7.547 ops/ms
Iteration   2: 7.886 ops/ms
Iteration   3: 8.049 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.827 ±(99.9%) 4.672 ops/ms [Average]
  (min, avg, max) = (7.547, 7.827, 8.049), stdev = 0.256
  CI (99.9%): [3.155, 12.500] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.397 ops/ms
# Warmup Iteration   2: 7.457 ops/ms
# Warmup Iteration   3: 8.470 ops/ms
Iteration   1: 8.403 ops/ms
Iteration   2: 8.425 ops/ms
Iteration   3: 8.590 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.473 ±(99.9%) 1.858 ops/ms [Average]
  (min, avg, max) = (8.403, 8.473, 8.590), stdev = 0.102
  CI (99.9%): [6.615, 10.331] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 2.235 ops/ms
# Warmup Iteration   2: 7.160 ops/ms
# Warmup Iteration   3: 8.073 ops/ms
Iteration   1: 8.081 ops/ms
Iteration   2: 8.022 ops/ms
Iteration   3: 8.323 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.142 ±(99.9%) 2.910 ops/ms [Average]
  (min, avg, max) = (8.022, 8.142, 8.323), stdev = 0.159
  CI (99.9%): [5.232, 11.052] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.133 ops/ms
# Warmup Iteration   2: 6.127 ops/ms
# Warmup Iteration   3: 6.822 ops/ms
Iteration   1: 6.825 ops/ms
Iteration   2: 6.633 ops/ms
Iteration   3: 6.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.695 ±(99.9%) 2.053 ops/ms [Average]
  (min, avg, max) = (6.626, 6.695, 6.825), stdev = 0.113
  CI (99.9%): [4.642, 8.747] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 13.001 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.450 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.239 ±(99.9%) 0.006 ms/op
Iteration   1: 3.958 ±(99.9%) 0.008 ms/op
Iteration   2: 3.920 ±(99.9%) 0.007 ms/op
Iteration   3: 4.045 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.974 ±(99.9%) 1.171 ms/op [Average]
  (min, avg, max) = (3.920, 3.974, 4.045), stdev = 0.064
  CI (99.9%): [2.804, 5.145] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 12.015 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.189 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.804 ±(99.9%) 0.005 ms/op
Iteration   1: 3.800 ±(99.9%) 0.005 ms/op
Iteration   2: 3.815 ±(99.9%) 0.005 ms/op
Iteration   3: 3.644 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.753 ±(99.9%) 1.724 ms/op [Average]
  (min, avg, max) = (3.644, 3.753, 3.815), stdev = 0.094
  CI (99.9%): [2.029, 5.477] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 14.064 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.353 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.925 ±(99.9%) 0.004 ms/op
Iteration   1: 4.074 ±(99.9%) 0.004 ms/op
Iteration   2: 3.923 ±(99.9%) 0.005 ms/op
Iteration   3: 3.771 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.923 ±(99.9%) 2.764 ms/op [Average]
  (min, avg, max) = (3.771, 3.923, 4.074), stdev = 0.152
  CI (99.9%): [1.158, 6.687] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 14.484 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 5.073 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.846 ±(99.9%) 0.009 ms/op
Iteration   1: 4.753 ±(99.9%) 0.004 ms/op
Iteration   2: 4.616 ±(99.9%) 0.008 ms/op
Iteration   3: 4.539 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.636 ±(99.9%) 1.981 ms/op [Average]
  (min, avg, max) = (4.539, 4.636, 4.753), stdev = 0.109
  CI (99.9%): [2.655, 6.618] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 13.561 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 4.907 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.450 ±(99.9%) 0.023 ms/op
Iteration   1: 3.944 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.757 ms/op
                 createUser·p0.50:   3.764 ms/op
                 createUser·p0.90:   4.514 ms/op
                 createUser·p0.95:   5.325 ms/op
                 createUser·p0.99:   8.331 ms/op
                 createUser·p0.999:  23.888 ms/op
                 createUser·p0.9999: 26.047 ms/op
                 createUser·p1.00:   27.623 ms/op

Iteration   2: 4.035 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.298 ms/op
                 createUser·p0.50:   3.850 ms/op
                 createUser·p0.90:   4.686 ms/op
                 createUser·p0.95:   5.284 ms/op
                 createUser·p0.99:   8.233 ms/op
                 createUser·p0.999:  21.561 ms/op
                 createUser·p0.9999: 27.918 ms/op
                 createUser·p1.00:   29.524 ms/op

Iteration   3: 3.926 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.891 ms/op
                 createUser·p0.50:   3.793 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.940 ms/op
                 createUser·p0.99:   7.832 ms/op
                 createUser·p0.999:  27.347 ms/op
                 createUser·p0.9999: 32.473 ms/op
                 createUser·p1.00:   33.063 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 241858
  mean =      3.968 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 946 
    [ 2.500,  5.000) = 227304 
    [ 5.000,  7.500) = 9875 
    [ 7.500, 10.000) = 2881 
    [10.000, 12.500) = 372 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.169 ms/op
     p(99.0000) =      8.135 ms/op
     p(99.9000) =     23.892 ms/op
     p(99.9900) =     30.638 ms/op
     p(99.9990) =     32.670 ms/op
     p(99.9999) =     33.063 ms/op
    p(100.0000) =     33.063 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 11.376 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.388 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.841 ±(99.9%) 0.013 ms/op
Iteration   1: 3.710 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.651 ms/op
                 existUser·p0.50:   3.551 ms/op
                 existUser·p0.90:   4.059 ms/op
                 existUser·p0.95:   4.619 ms/op
                 existUser·p0.99:   7.946 ms/op
                 existUser·p0.999:  22.792 ms/op
                 existUser·p0.9999: 28.095 ms/op
                 existUser·p1.00:   28.246 ms/op

Iteration   2: 3.907 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.210 ms/op
                 existUser·p0.50:   3.678 ms/op
                 existUser·p0.90:   4.596 ms/op
                 existUser·p0.95:   5.595 ms/op
                 existUser·p0.99:   8.258 ms/op
                 existUser·p0.999:  13.573 ms/op
                 existUser·p0.9999: 27.918 ms/op
                 existUser·p1.00:   28.574 ms/op

Iteration   3: 3.753 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.688 ms/op
                 existUser·p0.50:   3.600 ms/op
                 existUser·p0.90:   4.100 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   7.897 ms/op
                 existUser·p0.999:  27.977 ms/op
                 existUser·p0.9999: 34.569 ms/op
                 existUser·p1.00:   35.717 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 253330
  mean =      3.788 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1051 
    [ 2.500,  5.000) = 239776 
    [ 5.000,  7.500) = 8871 
    [ 7.500, 10.000) = 2660 
    [10.000, 12.500) = 568 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 68 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.210 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      8.028 ms/op
     p(99.9000) =     21.987 ms/op
     p(99.9900) =     33.751 ms/op
     p(99.9990) =     35.617 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.033 ±(99.9%) 0.211 ms/op
# Warmup Iteration   2: 4.795 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.148 ±(99.9%) 0.017 ms/op
Iteration   1: 4.095 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.493 ms/op
                 getUser·p0.50:   3.793 ms/op
                 getUser·p0.90:   4.743 ms/op
                 getUser·p0.95:   6.439 ms/op
                 getUser·p0.99:   8.733 ms/op
                 getUser·p0.999:  23.360 ms/op
                 getUser·p0.9999: 45.023 ms/op
                 getUser·p1.00:   52.888 ms/op

Iteration   2: 3.849 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.358 ms/op
                 getUser·p0.50:   3.666 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.776 ms/op
                 getUser·p0.99:   7.569 ms/op
                 getUser·p0.999:  17.564 ms/op
                 getUser·p0.9999: 27.646 ms/op
                 getUser·p1.00:   28.312 ms/op

Iteration   3: 3.952 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.812 ms/op
                 getUser·p0.50:   3.727 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   5.177 ms/op
                 getUser·p0.99:   8.159 ms/op
                 getUser·p0.999:  27.331 ms/op
                 getUser·p0.9999: 31.058 ms/op
                 getUser·p1.00:   35.389 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 242100
  mean =      3.963 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 227083 
    [ 5.000, 10.000) = 14019 
    [10.000, 15.000) = 625 
    [15.000, 20.000) = 72 
    [20.000, 25.000) = 104 
    [25.000, 30.000) = 143 
    [30.000, 35.000) = 33 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 11 
    [45.000, 50.000) = 7 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.358 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      8.356 ms/op
     p(99.9000) =     23.298 ms/op
     p(99.9900) =     31.699 ms/op
     p(99.9990) =     46.379 ms/op
     p(99.9999) =     52.888 ms/op
    p(100.0000) =     52.888 ms/op


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
# Warmup Iteration   1: 15.117 ±(99.9%) 0.220 ms/op
# Warmup Iteration   2: 5.524 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.897 ±(99.9%) 0.019 ms/op
Iteration   1: 4.739 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.761 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   6.455 ms/op
                 listUser·p0.99:   9.716 ms/op
                 listUser·p0.999:  23.429 ms/op
                 listUser·p0.9999: 26.706 ms/op
                 listUser·p1.00:   27.558 ms/op

Iteration   2: 4.680 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.507 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   9.355 ms/op
                 listUser·p0.999:  18.469 ms/op
                 listUser·p0.9999: 38.415 ms/op
                 listUser·p1.00:   40.894 ms/op

Iteration   3: 4.805 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.060 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   6.808 ms/op
                 listUser·p0.99:   9.945 ms/op
                 listUser·p0.999:  16.604 ms/op
                 listUser·p0.9999: 19.661 ms/op
                 listUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 202397
  mean =      4.741 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 169963 
    [ 5.000, 10.000) = 30751 
    [10.000, 15.000) = 1235 
    [15.000, 20.000) = 280 
    [20.000, 25.000) = 106 
    [25.000, 30.000) = 31 
    [30.000, 35.000) = 9 
    [35.000, 40.000) = 21 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.507 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.218 ms/op
     p(95.0000) =      6.128 ms/op
     p(99.0000) =      9.781 ms/op
     p(99.9000) =     18.960 ms/op
     p(99.9900) =     35.914 ms/op
     p(99.9990) =     39.584 ms/op
     p(99.9999) =     40.894 ms/op
    p(100.0000) =     40.894 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.827 ± 4.672  ops/ms
ClientPb.existUser                       thrpt       3   8.473 ± 1.858  ops/ms
ClientPb.getUser                         thrpt       3   8.142 ± 2.910  ops/ms
ClientPb.listUser                        thrpt       3   6.695 ± 2.053  ops/ms
ClientPb.createUser                       avgt       3   3.974 ± 1.171   ms/op
ClientPb.existUser                        avgt       3   3.753 ± 1.724   ms/op
ClientPb.getUser                          avgt       3   3.923 ± 2.764   ms/op
ClientPb.listUser                         avgt       3   4.636 ± 1.981   ms/op
ClientPb.createUser                     sample  241858   3.968 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.891           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.579           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.169           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.135           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.892           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.638           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.063           ms/op
ClientPb.existUser                      sample  253330   3.788 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.210           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.604           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.211           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.981           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.028           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.987           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.751           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.717           ms/op
ClientPb.getUser                        sample  242100   3.963 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.358           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.719           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.506           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.399           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.356           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.298           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.699           ms/op
ClientPb.getUser:getUser·p1.00          sample          52.888           ms/op
ClientPb.listUser                       sample  202397   4.741 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.507           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.218           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.128           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.781           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.960           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.914           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.894           ms/op
