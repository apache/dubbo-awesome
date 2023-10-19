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
# Warmup Iteration   1: 1.585 ops/ms
# Warmup Iteration   2: 3.365 ops/ms
# Warmup Iteration   3: 6.834 ops/ms
Iteration   1: 6.986 ops/ms
Iteration   2: 7.524 ops/ms
Iteration   3: 7.322 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.277 ±(99.9%) 4.953 ops/ms [Average]
  (min, avg, max) = (6.986, 7.277, 7.524), stdev = 0.272
  CI (99.9%): [2.324, 12.231] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.930 ops/ms
# Warmup Iteration   2: 5.989 ops/ms
# Warmup Iteration   3: 7.362 ops/ms
Iteration   1: 7.380 ops/ms
Iteration   2: 7.507 ops/ms
Iteration   3: 7.550 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.479 ±(99.9%) 1.615 ops/ms [Average]
  (min, avg, max) = (7.380, 7.479, 7.550), stdev = 0.089
  CI (99.9%): [5.864, 9.094] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.690 ops/ms
# Warmup Iteration   2: 5.420 ops/ms
# Warmup Iteration   3: 6.678 ops/ms
Iteration   1: 7.040 ops/ms
Iteration   2: 7.433 ops/ms
Iteration   3: 7.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.160 ±(99.9%) 4.319 ops/ms [Average]
  (min, avg, max) = (7.008, 7.160, 7.433), stdev = 0.237
  CI (99.9%): [2.842, 11.479] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.558 ops/ms
# Warmup Iteration   2: 4.840 ops/ms
# Warmup Iteration   3: 6.110 ops/ms
Iteration   1: 6.076 ops/ms
Iteration   2: 6.425 ops/ms
Iteration   3: 6.341 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.281 ±(99.9%) 3.323 ops/ms [Average]
  (min, avg, max) = (6.076, 6.281, 6.425), stdev = 0.182
  CI (99.9%): [2.957, 9.604] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 15.080 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 5.241 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.921 ±(99.9%) 0.005 ms/op
Iteration   1: 4.418 ±(99.9%) 0.006 ms/op
Iteration   2: 4.255 ±(99.9%) 0.009 ms/op
Iteration   3: 4.281 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.318 ±(99.9%) 1.595 ms/op [Average]
  (min, avg, max) = (4.255, 4.318, 4.418), stdev = 0.087
  CI (99.9%): [2.723, 5.913] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 14.442 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.612 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.389 ±(99.9%) 0.004 ms/op
Iteration   1: 4.193 ±(99.9%) 0.005 ms/op
Iteration   2: 4.168 ±(99.9%) 0.004 ms/op
Iteration   3: 3.869 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.077 ±(99.9%) 3.285 ms/op [Average]
  (min, avg, max) = (3.869, 4.077, 4.193), stdev = 0.180
  CI (99.9%): [0.792, 7.362] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 13.408 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.890 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.308 ±(99.9%) 0.003 ms/op
Iteration   1: 4.433 ±(99.9%) 0.005 ms/op
Iteration   2: 4.166 ±(99.9%) 0.007 ms/op
Iteration   3: 4.146 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.248 ±(99.9%) 2.921 ms/op [Average]
  (min, avg, max) = (4.146, 4.248, 4.433), stdev = 0.160
  CI (99.9%): [1.328, 7.169] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 15.503 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.876 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.908 ±(99.9%) 0.007 ms/op
Iteration   1: 5.017 ±(99.9%) 0.004 ms/op
Iteration   2: 5.249 ±(99.9%) 0.007 ms/op
Iteration   3: 4.840 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.035 ±(99.9%) 3.737 ms/op [Average]
  (min, avg, max) = (4.840, 5.035, 5.249), stdev = 0.205
  CI (99.9%): [1.298, 8.772] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 14.555 ±(99.9%) 0.204 ms/op
# Warmup Iteration   2: 5.328 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.819 ±(99.9%) 0.022 ms/op
Iteration   1: 4.432 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.925 ms/op
                 createUser·p0.50:   4.084 ms/op
                 createUser·p0.90:   5.439 ms/op
                 createUser·p0.95:   6.660 ms/op
                 createUser·p0.99:   10.147 ms/op
                 createUser·p0.999:  23.813 ms/op
                 createUser·p0.9999: 26.600 ms/op
                 createUser·p1.00:   27.296 ms/op

Iteration   2: 4.280 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.896 ms/op
                 createUser·p0.50:   4.047 ms/op
                 createUser·p0.90:   5.079 ms/op
                 createUser·p0.95:   5.612 ms/op
                 createUser·p0.99:   7.594 ms/op
                 createUser·p0.999:  15.668 ms/op
                 createUser·p0.9999: 26.723 ms/op
                 createUser·p1.00:   27.361 ms/op

Iteration   3: 4.207 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.868 ms/op
                 createUser·p0.50:   4.022 ms/op
                 createUser·p0.90:   4.899 ms/op
                 createUser·p0.95:   5.284 ms/op
                 createUser·p0.99:   7.970 ms/op
                 createUser·p0.999:  29.422 ms/op
                 createUser·p0.9999: 33.560 ms/op
                 createUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 223088
  mean =      4.304 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 349 
    [ 2.500,  5.000) = 196942 
    [ 5.000,  7.500) = 22037 
    [ 7.500, 10.000) = 2478 
    [10.000, 12.500) = 775 
    [12.500, 15.000) = 191 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.868 ms/op
     p(50.0000) =      4.047 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     23.953 ms/op
     p(99.9900) =     32.594 ms/op
     p(99.9990) =     34.507 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


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
# Warmup Iteration   1: 12.787 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 4.763 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.208 ±(99.9%) 0.015 ms/op
Iteration   1: 4.126 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.710 ms/op
                 existUser·p0.50:   3.903 ms/op
                 existUser·p0.90:   4.833 ms/op
                 existUser·p0.95:   5.595 ms/op
                 existUser·p0.99:   8.331 ms/op
                 existUser·p0.999:  12.624 ms/op
                 existUser·p0.9999: 28.074 ms/op
                 existUser·p1.00:   29.819 ms/op

Iteration   2: 3.972 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.923 ms/op
                 existUser·p0.50:   3.817 ms/op
                 existUser·p0.90:   4.448 ms/op
                 existUser·p0.95:   5.198 ms/op
                 existUser·p0.99:   7.840 ms/op
                 existUser·p0.999:  13.976 ms/op
                 existUser·p0.9999: 27.197 ms/op
                 existUser·p1.00:   27.558 ms/op

Iteration   3: 4.149 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.587 ms/op
                 existUser·p0.50:   3.916 ms/op
                 existUser·p0.90:   4.866 ms/op
                 existUser·p0.95:   5.448 ms/op
                 existUser·p0.99:   7.668 ms/op
                 existUser·p0.999:  13.550 ms/op
                 existUser·p0.9999: 30.704 ms/op
                 existUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 235247
  mean =      4.081 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 281 
    [ 2.500,  5.000) = 217419 
    [ 5.000,  7.500) = 14647 
    [ 7.500, 10.000) = 2006 
    [10.000, 12.500) = 587 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 97 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.587 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.448 ms/op
     p(99.0000) =      7.913 ms/op
     p(99.9000) =     13.894 ms/op
     p(99.9900) =     30.162 ms/op
     p(99.9990) =     30.921 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


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
# Warmup Iteration   1: 14.111 ±(99.9%) 0.206 ms/op
# Warmup Iteration   2: 5.406 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.406 ±(99.9%) 0.018 ms/op
Iteration   1: 4.434 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.556 ms/op
                 getUser·p0.50:   4.084 ms/op
                 getUser·p0.90:   5.554 ms/op
                 getUser·p0.95:   7.176 ms/op
                 getUser·p0.99:   9.437 ms/op
                 getUser·p0.999:  14.035 ms/op
                 getUser·p0.9999: 30.642 ms/op
                 getUser·p1.00:   31.359 ms/op

Iteration   2: 4.409 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.530 ms/op
                 getUser·p0.50:   4.043 ms/op
                 getUser·p0.90:   5.399 ms/op
                 getUser·p0.95:   7.225 ms/op
                 getUser·p0.99:   9.481 ms/op
                 getUser·p0.999:  15.720 ms/op
                 getUser·p0.9999: 29.385 ms/op
                 getUser·p1.00:   29.786 ms/op

Iteration   3: 4.145 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.448 ms/op
                 getUser·p0.50:   3.928 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   5.226 ms/op
                 getUser·p0.99:   8.454 ms/op
                 getUser·p0.999:  27.968 ms/op
                 getUser·p0.9999: 30.933 ms/op
                 getUser·p1.00:   33.161 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 221871
  mean =      4.325 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 90 
    [ 2.500,  5.000) = 198567 
    [ 5.000,  7.500) = 15742 
    [ 7.500, 10.000) = 6068 
    [10.000, 12.500) = 978 
    [12.500, 15.000) = 185 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 122 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.448 ms/op
     p(50.0000) =      4.014 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      6.873 ms/op
     p(99.0000) =      9.175 ms/op
     p(99.9000) =     24.322 ms/op
     p(99.9900) =     30.632 ms/op
     p(99.9990) =     33.027 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


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
# Warmup Iteration   1: 15.404 ±(99.9%) 0.244 ms/op
# Warmup Iteration   2: 6.455 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.027 ±(99.9%) 0.019 ms/op
Iteration   1: 5.152 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   4.874 ms/op
                 listUser·p0.90:   5.939 ms/op
                 listUser·p0.95:   7.234 ms/op
                 listUser·p0.99:   10.204 ms/op
                 listUser·p0.999:  26.935 ms/op
                 listUser·p0.9999: 30.041 ms/op
                 listUser·p1.00:   30.966 ms/op

Iteration   2: 4.935 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.515 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.636 ms/op
                 listUser·p0.95:   6.504 ms/op
                 listUser·p0.99:   9.077 ms/op
                 listUser·p0.999:  22.680 ms/op
                 listUser·p0.9999: 27.510 ms/op
                 listUser·p1.00:   29.622 ms/op

Iteration   3: 4.960 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.544 ms/op
                 listUser·p0.50:   4.751 ms/op
                 listUser·p0.90:   5.497 ms/op
                 listUser·p0.95:   6.431 ms/op
                 listUser·p0.99:   10.256 ms/op
                 listUser·p0.999:  18.743 ms/op
                 listUser·p0.9999: 21.430 ms/op
                 listUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 191506
  mean =      5.014 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 133229 
    [ 5.000,  7.500) = 51645 
    [ 7.500, 10.000) = 4804 
    [10.000, 12.500) = 929 
    [12.500, 15.000) = 324 
    [15.000, 17.500) = 186 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.290 ms/op
     p(50.0000) =      4.743 ms/op
     p(90.0000) =      5.693 ms/op
     p(95.0000) =      6.783 ms/op
     p(99.0000) =      9.896 ms/op
     p(99.9000) =     22.724 ms/op
     p(99.9900) =     29.121 ms/op
     p(99.9990) =     30.786 ms/op
     p(99.9999) =     30.966 ms/op
    p(100.0000) =     30.966 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.277 ± 4.953  ops/ms
ClientPb.existUser                       thrpt       3   7.479 ± 1.615  ops/ms
ClientPb.getUser                         thrpt       3   7.160 ± 4.319  ops/ms
ClientPb.listUser                        thrpt       3   6.281 ± 3.323  ops/ms
ClientPb.createUser                       avgt       3   4.318 ± 1.595   ms/op
ClientPb.existUser                        avgt       3   4.077 ± 3.285   ms/op
ClientPb.getUser                          avgt       3   4.248 ± 2.921   ms/op
ClientPb.listUser                         avgt       3   5.035 ± 3.737   ms/op
ClientPb.createUser                     sample  223088   4.304 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.868           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.047           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.095           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.857           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.733           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.953           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.594           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.603           ms/op
ClientPb.existUser                      sample  235247   4.081 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.587           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.871           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.751           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.448           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.913           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.894           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.162           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.031           ms/op
ClientPb.getUser                        sample  221871   4.325 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.448           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.014           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.063           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.873           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.175           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.322           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.632           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.161           ms/op
ClientPb.listUser                       sample  191506   5.014 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.290           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.743           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.693           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.783           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.896           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.724           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.121           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.966           ms/op
